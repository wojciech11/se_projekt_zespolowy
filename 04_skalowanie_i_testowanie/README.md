# Skalowanie i testowanie

## Skalowanie

- (1) pragmatism,
- consider - [v1/v2](https://katemats.com/blog/lean-software-development-build-v1s-and-v2s).
- macro- vs micro- services vs ... (monorepo),
- Patterns:

  - observability (from the customer perspective),
  - reverse proxy,
  - load balancers (round robin/sticky),
  - queues / pub sub,
  - caching,
  - CDNs.

Warto wykształcić wrażliwość na kod, który może być nie wydajny:

- https://app.codility.com/programmers/lessons/1-iterations/,
- co u mnie się kiedyś sprawdziło, [template projektu](https://github.com/wojciech11/cracking_coding_challenges).

## Testowanie

- functional tests, e.g, unit tests, integration test (a part of CI/CD),
- API end2end (periodical happy path tests on the prod),
- performance tests (e.g., [locust](https://locust.io/) or [gatling](https://gatling.io/)),
- iterations (+ retro after more complex implementation).

Do not forget about:

- internal demos for designers/product people,
- feedback from customers.

## References

- [12 factor apps](https://12factor.net/),
- [Bottlenecks of scaleups](https://martinfowler.com/articles/bottlenecks-of-scaleups/),
- [Martin Fowler blog on testing](https://martinfowler.com/tags/testing.html).
