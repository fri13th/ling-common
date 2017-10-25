# LING means Legacy Is Not Good

Ling is a minimalistic PHP MVC framework, carefully not to make a legacy issue. Inspired by Wordpress, Laravel and usa-framework.

One day I noticed that most of deveolper's daily work is not develop.

## Why legacy matters

1. You don't want to waste your time in seting-up another fancy next generation framework.
1. You don't want to maintain old and insecure framework.
1. You want to adopt some coolest features or latest security patches without conflicting.
1. You want to focus on the business logic, running app, making money.

## How can we achieve legacy-free

1. All parts of framework must be separated and independent modules(Except config).
1. All future codes must support previous APIs.
1. If there needs some breaking changes in some module, make another module and migrate to it.
1. Allow separate modules at the sametime for convenient migration.

## We need these policy for legacy-free

1. Use modern PHP's best practices, include FP.
1. Prefer native features always.
1. Use composer for making all modules pluggable.
1. Use hook for separating each modules.

## There are some more goals to solve legacy issue

1. IDE-centric Development. Don't use reflection and DI. Those complicate dependencies.
1. Use code generator for separating environment to actual code.
1. Complete documents and sample sites.

We don't aim full featured all-in-one framework. If you want all-in-one, I recommend Laravel.
