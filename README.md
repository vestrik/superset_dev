# superset_dev
## Develop for SuperSet

<br>Error:
<br>`failed to solve: process "/bin/sh -c npm run ${BUILD_CMD}" did not complete successfully: exit code: 1`
<br>Fix:
1. increate memory for docker - https://stackoverflow.com/questions/43460770/docker-windows-container-memory-limit
2. https://github.com/apache/superset/discussions/30197

<br>Error:
`[webpack-cli] Failed to load '/home/user/superset/superset-frontend/webpack.config.js' config`
`[webpack-cli] Error: Can not access zstd! Is it installed?`
<br>Fix: 
1. Download https://github.com/facebook/zstd/releases zstd-vX.X.X-win64.zip
2. Place zstd.exe in a directory that is included in your system's PATH. Common directories include C:\Windows\System32
3. Verify Installation: cmd - where zstd.exe
