# Send Me Your Prompt

A static page for asking people to send the prompt behind an AI-generated
document, not just the generated output.

## Development

This is a single static HTML page deployed on Cloudflare Pages.

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8765/>.

## Deployment

Deploy with Cloudflare Pages Direct Upload:

```sh
npx wrangler pages deploy . --project-name sendyourprompt --branch main
```

The production custom domain is <https://sendmeyourprompt.com/>.

## Credits

Styled after [nohello.net](https://www.nohello.net/en/), which is licensed
under MIT. Avatars are reused in the same spirit as nohello.net's Slack-style
examples.

## License

MIT
