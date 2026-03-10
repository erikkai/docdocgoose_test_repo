# Doc Doc Goose - Test Repository
This repository is a sample project you can use to try out the [Doc Doc Goose](https://github.com/erikkai/docdocgoose) CLI. 

Doc Doc Goose is a tool that monitors and detects when documentation becomes invalid. See the main repository for more details about how the tool works.

## How to Use This Repo

This repository is meant to be used with the [DocDocGoose](https://github.com/erikkai/docdocgoose) CLI.

### 1. Clone the repositories

Clone both the DocDocGoose project and this test repository:

```bash
git clone https://github.com/erikkai/docdocgoose.git
git clone https://github.com/erikkai/docdocgoose_test_repo.git
```

### 2. Install Doc Doc Goose 

From inside the docdocgoose repository, install the CLI in editable mode:

```
cd docdocgoose
pip install -e .
```

### 3. Move into the test repository

```
cd ../docdocgoose_test_repo
```

### 4. Initialize Doc Doc Goose 

```
ddg init
```

### 5. Run a scan 

```
ddg scan
```

Scan results will be written to:

```
.docdocgoose/logs/scan_log.json
```

