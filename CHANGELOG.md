# 0.2.0

- Feature: add support for using `DataSource` and `EntityManager` with transactional [#2](https://github.com/Aliheym/typeorm-transactional/issues/2)

# 0.3.0

- Feature: add maximum hook handlers options [#13](https://github.com/Aliheym/typeorm-transactional/issues/13)
- Fix: improve checks to support newest TypeORM versions [#15](https://github.com/Aliheym/typeorm-transactional/issues/9)

# 0.4.0

- Feature: add support for TypeORM custom and extend repositories [#19](https://github.com/Aliheym/typeorm-transactional/issues/19). Thanks this PR [#14](https://github.com/Aliheym/typeorm-transactional/pull/14).
- Chore: keep comments/docs [#17](https://github.com/Aliheym/typeorm-transactional/issues/17). Thanks this PR [#18](https://github.com/Aliheym/typeorm-transactional/pull/18).

# 0.4.1

- Feature: wrapInTransaction infer to the original function. Thanks this PR [#21](https://github.com/Aliheym/typeorm-transactional/pull/21).

# 0.5.0

- Feature: add [Async Local Storage](https://nodejs.org/api/async_hooks.html#class-asynclocalstorage) support ([#39](https://github.com/Aliheym/typeorm-transactional/pull/39)).
- Refactor: remove unnecessary patch ([#29](https://github.com/Aliheym/typeorm-transactional/pull/29)).
- Refactor: improve the tests for all use cases.

# 0.6.0

- Chore: bump minimum supported Node.js version to `>=16.0.0` (aligns with `AsyncLocalStorage` GA support).
- Chore: bump TypeScript compilation `target`/`lib` to `es2021`, emitting native `async`/`await` (and other ES2017+ syntax) instead of transpiled state machines for smaller and faster output.
