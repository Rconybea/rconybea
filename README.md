## Hello,  Roland here 👋
- I'm Roland Conybeare, a software developer engaged in continuous learning.
- Several decades of experience in the financial industry, working mostly in c++
- Trying to solve problems so that they "stay solved" -- easier said than done!

## Links
• <a href="https://rconybea.github.io/web">website</a>
&nbsp;
• <a href="https://www.linkedin.com/in/roland-conybeare-3640ab4" rel="noreferer">
   <img src="https://skillicons.dev/icons?i=linkedin" width="16px"> linkedin
  <a>
•

## Areas of Interest
- Developer productivity.  Member of the church of emacs.  Trying to write better documentation.
- Numerical programming.  Kalman filters, PDE solvers, stochastic processes etc.
- Performance oriented programming.  For example low-latency schedulers,  some lockfree algos.
- Integration with REPL tools.  Author of various scheme-based DSLs,  more recently working with pybind11.

## Projects
- <a href="https://rconybea.github.io/web/sw/xo.html">XO</a>: a set of cooperating c++ libraries, with python bindings, for simuation and complex event processing.

   | library                                                                   | pybind                                                                         | hdr-only | description            | outside deps        |
   |---------------------------------------------------------------------------|--------------------------------------------------------------------------------|----------|------------------------|---------------------|
   | <a href="https://github.com/Rconybea/xo-jit">xo-jit</a>                   | <a href="https://github.com/Rconybea/xo-pyjit">xo-pyjit</a>                    |          | LLVM jit               | llvm                |
   | <a href="https://github.com/Rconybea/xo-expression">xo-expression</a>     | <a href="https://github.com/Rconybea/xo-pyexpression">xo-pyexpression</a>      |          | AST impl               |                     |
   | <a href="https://github.com/Rconybea/xo-websock">xo-websock</a>           | <a href="https://github.com/Rconybea/xo-pwebsock">xo-pywebsock</a>             |          | websocket server       | websockets, jsoncpp |
   | <a href="https://github.com/Rconybea/xo-kalmanfilter">xo-kalmanfilter</a> | <a href="https://github.com/Rconybea/xo-pykalmanfilter">xo-pykalamnfilter</a>  |          | linear kalman filter   | eigen               |
   | <a href="https://github.com/Rconybea/xo-process">xo-process</a>           | <a href="https://github.com/Rconybea/xo-pyprocess">xo-pyprocess</a>            |          | stochastic processes   |                     |
   | <a href="https://github.com/Rconybea/xo-simulator">xo-simulator</a>       | <a href="https://github.com/Rconybea/xo-pysimulator">xo-pysimulator</a>        |          | event-based simulation |                     |
   | <a href="https://github.com/Rconybea/xo-reactor">xo-reactor</a>           | <a href="https://github.com/Rconybea/xo-pyreactor">xo-pyreactor</a>            |          | queueing system        |                     |
   | <a href="https://github.com/Rconybea/xo-reflect">xo-reflect</a>           | <a href="https://github.com/Rconybea/xo-pyreflect">xo-pyreflect</a>            |          | c++ reflection         |                     |
   | <a href="https://github.com/Rconybea/xo-unit">xo-unit</a>                 | <a href="https://github.com/Rconybea/xo-pyunit">xo-pyunit</a>                  |        Y | constexpr units        |                     |
   | <a href="https://github.com/Rconybea/xo-ratio">xo-ratio</a>               |                                                                                |        Y | constexpr exact ratios |                     |
   | <a href="https://github.com/Rconybea/randomgen">xo-randomgen</a>          |                                                                                |        Y | xoshiro256** rng       |                     |
   | <a href="https://github.com/Rconybea/indentlog">xo-indentlog</a>          |                                                                                |        Y | structured logging     |                     |
   | <a href="https://github.com/Rconybea/xo-flatstring">xo-flatstring</a>     |                                                                                |        Y | constexpr strings      |                     |

- <a href="https://github.com/rconybea/cmake-examples">cmake-examples</a>: progressive series of cmake examples, starting from hello world.
- <a href="https://github.com/rconybea/docker-cpp-builder">docker-cpp-builder</a>: example nix-built docker container for generic c++ builds
- <a href="https://github.com/rconybea/docker-nix-builder">docker-nix-builder</a>: example nix-built docker container (with nix made available at build time)
- <a href="https://rconybea.github.io/web/env/cleanmbox.html">cleanmbox</a>: automatically tidy email
- <a href="https://rconybea.github.io/web/env/emacs-setup.html">.emacs setup</a>: terse `.emacs` walkthrough; includes c++ lsp setup and org-mode publishing

## Currently learning about
- 2024
  - getting familiar with c++20/c++23 features;  in particular constexpr, non-type template parameters, concepts.
  - getting started with SIMD vector instructions,  in particular AVX2
  - getting started with llvm,  via Kaleidoscope tutorial.
  - documentation using doxygen + sphinx + breathe.
- 2023
  - in-memory B-tree
  - learning how to put nix to work,  in particular for projects not present in nixpkgs.
  - continuous integration using github actions.
  - custom docker containers for github CI, automagically prepared via nix.
  - diving into cmake, focusing on multi-repo builds
- 2022
  - xoshiro256**;  fast RNG.
  - kalman filter using Eigen for matrix algorithms.
  - websockets
  - pybind11
- once upon a time
  - garbage collection algorithms.

<!--
**Rconybea/rconybea** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
