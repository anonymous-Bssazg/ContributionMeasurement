# Author with suspicious commit

In the file, the data are in the following format:

```json
{
    "Netflix/netflix-commons": [    // project
        {
            "author": "aspyker@netflix.com",    // email of author, from git log, not GitHub
            "by_commit": 0.011111111111111112,  // Share by commit number, calculated as by_commit = commit_by_the_author / total_commit
            "by_deffort": 0.0   // Share by deffort, calccalculated as by_deffort = total_deffort_by_author / total_deffort
        },
}
```
