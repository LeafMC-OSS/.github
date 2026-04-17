# OpenLeaf - LeafMC Open Sourced (partially)

> Community-driven ecosystem, built to last, free to use.

OpenLeaf builds and maintains high-performance software for the Minecraft ecosystem and beyond. We operate on an Open-Core model. While our proprietary server network logic remains private, the tools, libraries, standalone plugins, and infrastructure wrappers we build to support it are open-source.

## What We Open-Source

We only share code that functions independently.

* **Standalone Plugins:** Modular Paper plugins solving specific server management problems.
> More coming soon 👀

## Tech Stack & Standards

Review the individual project README before writing code.

* **Minecraft Ecosystem:** Strictly Java 21 using modern Paper/Brigadier APIs. Legacy Bukkit code is rejected.
* **Build Systems:** Gradle Kotlin DSL across all JVM projects.


## How to Contribute

We maintain strict code quality standards. Follow this pipeline for your code to be merged:

1. **Find an Issue:** Look for "good first issue" or "help wanted" tags. For major features, open an Issue to discuss it first.
2. **Branch Out:** Fork the repository and use standard branching (e.g., feat/your-feature or fix/issue-name).
3. **Keep it Testable:** Code must compile and test locally without access to private .jar files. Use provided mock environments if applicable.
4. **Pass the Build:** All repositories use GitHub Actions CI/CD. Your PR must compile cleanly. Code triggering deprecation warnings or failing the build will not be reviewed.
5. **Open a PR:** Provide a clear description of the changes, the reasoning, and local testing methods. Keep it focused on one feature per PR.

## License

Each repository specifies its own license. Most of our open-source ecosystem is licensed under MIT unless noted otherwise. Check the LICENSE file in the specific project.
