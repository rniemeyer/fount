## 0.1.X

### 0.1.0

 * #7 - Add better error reporting - include all unresolvable keys
 * #6 - Export canResolve to allow consumers to check in advance
 * Backfill dependencies from NPM modules when available
 * Add support for bulk registration

## 0.0.X

### 0.0.6
 * Fix bug where things like sinon.stub cause dependency check to throw an exception
 * When a function's dependencies cannot be resolved, return the function rather than throw an exception
