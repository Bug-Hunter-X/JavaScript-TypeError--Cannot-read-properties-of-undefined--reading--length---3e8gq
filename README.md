# JavaScript Null and Undefined Handling Error

This repository demonstrates a common error in JavaScript when handling null and undefined values. The `foo` function attempts to access the `length` property of the input `x`, which can lead to a `TypeError` if `x` is undefined.  The solution demonstrates how to properly handle null and undefined values using explicit checks.

## Bug

The original code fails to handle the case where the input is undefined. Attempting to access `x.length` when `x` is undefined throws a `TypeError`.

## Solution

The solution modifies the function to explicitly check for both `null` and `undefined` values before accessing the `length` property. This prevents the `TypeError` from occurring.
