Application is written with Python. Linting is done with Pylint. Testing is done with unittest unit testing framework. Distribution package is done with Python build project.

CI can be done using for example CircleCI, TeamCity, HCL Accelerate, LaunchDarkly, Buddy, Bamboo, GoCD, Codeship, Buildbot, Integritry, Strider, Autorabbit, Final Builder, Wercker, Buildkite, Semaphore, CruiseControl, Bitrise or Urbancode.

Since the project is quite small, using cloud-based solution seems easiest solution. Cloud-based solution doesn’t take resources for setting up and maintaining environment from small team. As long as the application remains small, limited resources from cloud-based server doesn’t restrict development. If the application expands in the future, server might start to hinder developing and maintaining application.

From security side, self-hosted server is much safer solution. Safety critical code can be controlled much easier with own server. Attackers have harder time getting access to business-critical code with on-site server and it is also harder to inject altered code or source files to CI pipeline.

If application requires special steps with CI, own server offers more flexibility to setup environment. It might even be impossible to do everything with cloud-based solution. Jenkins for example offers many plugins, which helps you to get things done.

From pricing point of view, cloud-based solution offers smaller initial costs and can be cheaper for small projects, but self-hosted solution offers more predictable pricing with almost constant pricing.
