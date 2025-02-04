# guard

Run the `guard` NestJS generator with Nx project support.

## Usage

```bash
nx generate guard ...
```

By default, Nx will search for `guard` in the default collection provisioned in `angular.json`.

You can specify the collection explicitly as follows:

```bash
nx g @nrwl/nest:guard ...
```

Show what will be generated without writing to disk:

```bash
nx g guard ... --dry-run
```

## Options

### directory

Alias(es): d,path

Type: `string`

Directory where the generated files are placed.

### flat

Default: `true`

Type: `boolean`

Flag to indicate if a directory is created.

### language

Type: `string`

Possible values: `js`, `ts`

Nest guard language.

### name

Type: `string`

The name of the guard.

### project

Alias(es): p

Type: `string`

The Nest project to target.

### skipFormat

Default: `false`

Type: `boolean`

Skip formatting files.

### unitTestRunner

Default: `jest`

Type: `string`

Possible values: `jest`, `none`

Test runner to use for unit tests.
