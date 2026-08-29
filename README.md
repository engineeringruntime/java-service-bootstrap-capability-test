# java-service-bootstrap-capability-test

This repo was bootstrapped by this capability - https://github.com/kishore-gutta/engineering-runtime-capabilities/blob/main/capabilities/github/java-service-scaffold-and-ship.md

A Maven service scaffolded end to end by the Engineering Runtime — no
directory was created by hand, no file was pushed by a raw CLI, and every
step below is in the runtime audit log.

- Package: com.example.demo
- Entry point: src/main/java/com/example/demo/App.java
- Pipeline: .github/workflows/java-ci.yml (workflow_dispatch enabled)

Build it locally with: mvn -B package
