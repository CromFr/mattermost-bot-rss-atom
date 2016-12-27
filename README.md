
# Mattermost bot for pulling RSS/Atom feeds

Based on https://github.com/bitbackofen/Rss-Atom-Feed-Integration-for-Mattermost

```sh
# Copy settings file
cp ./src/settings.py /path/to/custom/settings.py

# Run container
docker run -v /path/to/custom/settings.py:/opt/bot-rss-atom/settings.py cromfr/mattermost-bot-rss-atom
```
