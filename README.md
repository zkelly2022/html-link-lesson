# Linking It All Together

Now that you've seen how to create different types of links, it's time for you to try it for yourself!

## Instructions

1. Open index.html and review the code and comments.
2. Near the top of the page, use an `<img>` tag to embed `html.jpeg`, which is in the `images` subfolder.
    1. This is an called a **relative link**.
    2. It depends on the fact that to get from this page, to html.jpeg, we first have to go into the images folder.
3. Under that, create a link to a website of your choice. Have it open in a new window.
    1. See the `target` attribute on the [W3Schools &lt;a&gt; tag page for help on opening in a new tab/window](https://www.w3schools.com/tags/tag_a.asp)
    2. This is called an **absolute link**.
    3. This is because no matter where we are, this link will always take us to the website you want it to.
4. Next use the `id` attribute to give each paragraph below an id.
    1. See the example one already in `paragraph1`.
    2. I recommend calling them `paragraph1`, `paragraph2`, and `paragraph3`.
5. Turn each of the items under "Navigation" to a link to each paragraph.
    1. Notice that you type a # and then the name of the id to create a link within the page. (ex. `<a href="#paragraph1>`)
6. Add several line breaks between each paragraph and then test the links.
7. Give the h1 at the top of the page an id like "top" and create a link at the bottom of the page called "Back to Top."

## Congratulations

You're done! You have:

* used relative linking to reference a file on your own website
* created a link to another website
* linked to different parts of the same web page!