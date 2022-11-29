<script lang="ts">
let websiteName = 'Research Solutions Dev';
let websiteUrl = 'https://ReSol.Dev';
</script>

<div data-name="top-bar">
    <a href="{websiteUrl}">
        <img src="favicon.png" alt="{websiteName}" width="30" />
        <span>{websiteName}</span>
    </a>
</div>

<div data-name="hero">
    <div class="container">
        <h4>Be a part of the solutions!</h4>
        
        <small>Connect with Researchers 🔬 and Developers ‍💻 to shape the future of research solutions ✨</small>

        <div data-name="discussion-action">
            <a href="https://github.com/ReSolDev/resoldev.github.io/discussions">Go to Discussions</a>
        </div>
    </div>
</div>
    
<div data-name="announcement">
    <div class="container">
        <h3>What is ReSol.Dev?</h3>
        <section>
            A community-managed discussion board focused on addressing the shortcomings of research tools. Researchers and developers are invited to discuss what improvements are most desired, which ones should be prioritized, and what it takes to materialize them. This webpage and all discussions are hosted on <a href="https://github.com/ReSolDev">GitHub</a>. Please follow <a href="https://twitter.com/ReSolDev">@ReSolDev</a> on Twitter for updates.
        </section>
    </div>
</div>

<div data-name="">
    <div class="container">
        <section>
            <h3>➤ How can I contribute?</h3>
            <section>
                If you are a researcher, share what technological improvements you need the most and how valuable they would be to your research.<br>
                If you are a software developer, share what technological improvements are possible and what it takes for those improvements to materialize.
            </section>
        </section>
    </div>
</div>

<div data-name="">
    <div class="container">
        <section>
            <h2>🚧 This section is under construction! 🚧</h2>
        </section>
    </div>
</div>



<style lang="scss" global>
body {
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
section {
    line-height: 1.5rem;
}
.container {
    max-width: 960px;
    margin: auto;
    padding: 1rem;
}
[data-name=top-bar] {
    padding: 10px 20px;
    border-bottom: 1px solid #e5e5e5;
    font-size: 1.3em;
    background-color: #fbfbfb;
    a {
        text-decoration: none;
        color: inherit;
    }
    img {
        vertical-align: middle;
        margin-right: 5px;
    }
    span {
        vertical-align: middle;
        font-weight: 600;
    }
}
[data-name=hero] .container {
    padding: 3rem 1rem;
    font-size: 2.5rem;
    h4 {
        text-shadow: rgb(187, 187, 187) 0px 0px 3px;
        margin: 0;
    }
    small {
        font-size: 1.13rem;
    }
}

[data-name=announcement] {
    margin-bottom: 1rem;
    padding-bottom: 1rem;
    background-color: #d2e3e3;
    img {
        vertical-align: middle;
    }
}

[data-name=discussion-action] {
    text-align: center;
    padding-top: 1.2rem;
    a {
        text-decoration: none;
        color: white;
        background-color: rgb(132, 15, 187);
        padding: .5rem 1rem;
        border-radius: 10px;
        font-size: 1.2rem;
    }
}
</style>