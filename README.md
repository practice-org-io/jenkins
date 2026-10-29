# Jenkins Pipeline Practice

Jenkins declarative pipeline examples. Two files: a standard `Jenkinsfile` and a Docker-based pipeline variant.

## Files

| File | Purpose |
|---|---|
| `Jenkinsfile` | Standard declarative pipeline with stages |
| `Jenkinsfile.dcl` | Docker-based pipeline variant |

## Quick Start

```bash
# Copy to your Jenkins server
cp Jenkinsfile /var/lib/Jenkins/Jobs/MyJob/

# Or run with jenkins-cli
jenkins-cli run-job MyJob
```

## Related Practice
