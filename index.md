---
layout: default
---

{% capture readme %}

<div markdown="1">
{% include_relative README.md %}
</div>

{% endcapture %}


<body class="d-flex flex-column flex-items-center">
    <header class="d-flex flex-justify-center flex-items-center flex-column flex-sm-row my-4 my-sm-6 mx-2">
        <img
            src="assets/img/headshot.jpg"
            alt="portrait"
            class="avatar avatar-scale mb-4 mb-sm-0 mr-sm-6"
        />
        <div>
            <h1 class="h1 text-light text-center text-sm-left">Brady Lenz</h1>
            <h2 class="h3 text-normal text-mono color-fg-muted text-center text-sm-left">
                Software Engineer
                <a
                    href="https://www.webex.com/webex-assistant.html"
                    target="_blank"
                    rel="noopener noreferrer"
                >
                    @cisco
                </a>
            </h2>
        </div>
    </header>
    <main class="mx-2 mb-2">
        <article class="Box">
            <header class="Box-header">
                <nav>
                    <ol>
                        <li class="breadcrumb-item">
                            <a
                                href="https://github.com/bradylenz/bradylenz"
                                target="_blank"
                                rel="noopener noreferrer"
                            >
                                bradylenz
                            </a>
                        </li>
                        <li class="breadcrumb-item breadcrumb-item-selected">
                            <a
                                href="https://github.com/bradylenz/bradylenz/blob/main/README.md"
                                target="_blank"
                                rel="noopener noreferrer"
                            >
                                README.md
                            </a>
                        </li>
                    </ol>
                </nav>
            </header>
            <section class="Box-body markdown-body">
                {{readme}}
            </section>
        </article>
    </main>
</body>
