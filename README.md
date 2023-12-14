 <!-- LTeX: disabled=true -->
# PDF summarizer for Alfred<!-- LTeX: enabled=true -->
![Download count](https://img.shields.io/github/downloads/chrisgrieser/pdf-summarizer-alfred/total?label=Total%20Downloads&style=plastic)
![Last release](https://img.shields.io/github/v/release/chrisgrieser/pdf-summarizer-alfred?label=Latest%20Release&style=plastic)

Get summaries of your PDFs via [ChatPDF](https://www.chatpdf.com/) with just one
hotkey.

Requires a ChatPDF API key, which is (currently) free for 5000 PDF pages / 500
requests per month.

<img width="60%" alt="Showcase Universal Action" src="https://github.com/chrisgrieser/pdf-summarizer-alfred/assets/73286100/a4c8e7e7-cb56-4727-9a0e-ddfc91461c11">

<img src="./assets/showcase.gif" alt="showcase gif" width=70%>

## Installation & Setup
[➡️ Download the latest release.](./releases/latest)

The workflow auto-updates via Alfred's workflow-update mechanism.

**Get a ChatPDF API key:**
1. Go to <https://www.chatpdf.com/>
2. Scroll to the bottom of the page.
3. In the footer, click `My Account`. You are prompted to create an account if
   you do not have one yet.
4. In `My Account`, expand the `Developer` settings. You can find your API key there:

<img src="./assets/how-to-get-api-key.png" alt="how to find the API key" width=40%>

> [!NOTE]
> **Advanced Users:** Instead of entering the API key directly, you can also
> enter `.zshenv` into the API key field. The workflow then uses the key
> exported as `CHATPDF_API_KEY` in your `.zshenv`.
