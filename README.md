# Snapshot for Claude

![Snapshot](assets/icon.png)

Turn your photo into a real sports card or trading card with Snapshot. Create a front and back using our static templates, choose both sides from Snapshot's AI generator, or upload finished artwork made elsewhere. Preview Rookie Boxes, Bulk Boxes, oversized MEGA cards and numbered slabs with the same products and production process as our website.

This is the submission candidate. Directory approval and publication are pending.

## Connect and create

1. Install this plugin in Claude. Open its Connectors tab and connect Snapshot. Alternatively, add `https://www.makesnapshots.com/api/claude/mcp` as a custom connector.
2. Sign in to your own Snapshot account on makesnapshots.com and allow the requested card and cart access.
3. Ask Claude to open the Snapshot card studio. Use **Upload photo** or the front/back upload controls to select your image. Images are uploaded privately to your account. A photo attached only to the conversation may need to be selected again in the studio; do not paste private file links into the chat.
4. Choose a Snapshot template or AI style and provide the details to print. Review the front and back, then choose a product, finish, quantity and any slab label text.
5. Preview, **Add to cart**, then **View cart**. Complete shipping, taxes, discounts and payment on Snapshot. No payment credentials are collected in Claude.

Claude does not natively generate photographic artwork. Snapshot's own generator supplies the AI card and matching-back options, using the same account allowance as the website. Static-template creation includes background removal. Uploads support PNG, JPEG and WebP, under 20 MB and 40 megapixels. Saved creations can be reopened through **My creations**.

A free Snapshot account is required to save cards. Physical products are paid; current prices appear in the preview, with shipping and tax at checkout. Claude access and custom-connector availability depend on your Anthropic plan and workspace settings.

## Try it

- "Open Snapshot so I can upload a photo and make a physical card."
- "Show me Snapshot's static card templates. I want a front and back."
- "Use Snapshot AI to create a card from my uploaded photo and the details I provide."
- "Preview my saved design in a 1/1 slab."
- "Help me make a Bulk Box for the team."

For finished artwork, upload both sides or let Snapshot generate matching backs from your front and supplied details. Snapshot is intended for adult collectors, parents and authorized team organizers. Use images you have permission to print. A 1/1 identifies one slab in its print run; it does not imply exclusive artwork ownership or third-party grading.

## Data, troubleshooting and support

Selected photos, optional logos, supplied names and statistics, and resulting artwork are stored privately in the connected Snapshot account. The studio uploads selected files directly to Snapshot storage and shares an opaque file reference with Claude. Snapshot uses its existing image-processing and generation providers for requested operations. The embedded studio receives temporary private preview links. See the full [Claude data disclosure](https://www.makesnapshots.com/privacy#claude).

If a connection expires, reconnect Snapshot. If a generation is still running, use **Check progress** or **My creations**; do not start a duplicate. If you have already added a slab, open the existing cart item to change it. Checkout may ask you to sign in to the same Snapshot account you connected in Claude.

[Setup](https://www.makesnapshots.com/claude) · [Manage/disconnect](https://www.makesnapshots.com/claude/connect) · [Privacy](https://www.makesnapshots.com/privacy#claude) · [Terms](https://www.makesnapshots.com/terms) · [Support](https://www.makesnapshots.com/contact)

Disconnecting does not delete saved cards or orders. Contact privacy@makesnapshots.com for access, correction or deletion, or support@makesnapshots.com for help.

## Package

This repository contains the plugin manifest, remote MCP configuration, instructions and brand icon. No credentials or backend source are included. Validate it with `claude plugin validate .`. MIT license applies to the plugin software and documentation; Snapshot trademarks and hosted services remain separate. Claude Code supports the remote tools, while the interactive image picker and visual selections require a Claude host with MCP Apps support; use Snapshot's website if those controls are unavailable.
