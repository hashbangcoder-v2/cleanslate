# Tabula Rasa

The source for **Tabula Rasa**, a Hugo and PaperMod technical blog by **Joat Mone**.

## Write a post

Create a Markdown file in `content/posts/` or run:

```sh
hugo new content posts/my-post.md
hugo server -D
```

Code fences are highlighted automatically. Put ordinary images beside an `index.md`
file in a page bundle, or under `static/images/`.

### Tweet

```go-html-template
{{< tweet user="OpenAI" id="1234567890" >}}
```

### Mermaid diagram

```go-html-template
{{< mermaid >}}
flowchart LR
  Prompt --> Model --> Evaluation
{{< /mermaid >}}
```

### Data chart

```go-html-template
{{< chart type="line" label="Score" labels="v1,v2,v3" values="62,74,83" >}}
```

Pushing to `main` builds and publishes the site through GitHub Pages.
