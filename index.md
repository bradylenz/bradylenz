---
layout: default
---

{% capture readme %}

<div markdown="1">
{% include_relative README.md %}
</div>

{% endcapture %}


<body class="d-flex flex-column flex-items-center flex-justify-center m-2">
    <main>
        <article class="Box">
            <header class="Box-header">
                <nav>
                    <ol>
                        <li class="breadcrumb-item">
                            <a href="https://github.com/bradylenz/bradylenz">bradylenz</a>
                        </li>
                        <li class="breadcrumb-item breadcrumb-item-selected">
                            <a href="https://github.com/bradylenz/bradylenz/blob/main/README.md">README.md</a>
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
