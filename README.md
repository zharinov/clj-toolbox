# clj-toolbox

The composite GitHub action which combines:
- [`actions/setup-java`](https://github.com/actions/setup-java/)
- [`graalvm/setup-graalvm`](https://github.com/graalvm/setup-graalvm)
- [`actions/setup-clojure`](https://github.com/DeLaGuardo/setup-clojure)

For the options reference, see [the manifest file](https://github.com/zharinov/clj-toolbox/blob/main/action.yml).

Note that default versions for GraalVM and Clojure CLI are hardcoded for the reproducibility.
