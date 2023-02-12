This is a [DVC Studio](https://studio.iterative.ai) testing (fixture) repository.

## `<root>/` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='true'
OPT_INIT_GIT='true'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='false'
OPT_REMOTE='private-s3'
OPT_SUBDIR=''
OPT_TESTING_REPO='true'
```

## `<root>/nested` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='false'
OPT_INIT_GIT='false'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='false'
OPT_REMOTE='private-ssh'
OPT_SUBDIR='nested'
OPT_TESTING_REPO='true'
```

## `<root>/slice` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='false'
OPT_INIT_GIT='false'
OPT_NON_DVC='true'
OPT_REGISTER_MODELS='false'
OPT_REMOTE='private-ssh'
OPT_SUBDIR='slice'
OPT_TESTING_REPO='true'
```

## `<root>/nested/private` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='true'
OPT_INIT_DVC='true'
OPT_INIT_GIT='false'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='true'
OPT_REMOTE='private-s3'
OPT_SUBDIR='nested/private'
OPT_TESTING_REPO='true'
```

## `<root>/nested/public` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='true'
OPT_INIT_GIT='false'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='false'
OPT_REMOTE='public-s3'
OPT_SUBDIR='nested/public'
OPT_TESTING_REPO='true'
```

## `<root>/nested/private/slice` config

```bash
OPT_BRANCHES='false'
OPT_DVC_TRACKED_METRICS='false'
OPT_INIT_DVC='false'
OPT_INIT_GIT='false'
OPT_MODEL_NAME='text-classification'
OPT_NON_DVC='false'
OPT_REGISTER_MODELS='false'
OPT_REMOTE='private-ssh'
OPT_SQUASH_COMMITS='true'
OPT_SUBDIR='nested/private/slice'
OPT_TAGS='false'
OPT_TAG_MODELS='false'
OPT_TESTING_REPO='true'
```
