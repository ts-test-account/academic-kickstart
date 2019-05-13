+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "Academic Kickstart"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "DarkGreen"
  gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

Welcome to the **Academic Kickstart** template!

<p>コンテンツ</p>
            <div id="users">
                <input class="search" placeholder="Search" />
                <button class="sort" data-sort="name">
                    Sort by name
                </button>
                <table>
                    <!-- IMPORTANT, class="list" have to be at tbody -->
                    <tbody class="list">
                        <tr>
                            <td class="name">Jonny Stromberg</td>
                            <td class="born">1986</td>
                        </tr>
                        <tr>
                            <td class="name">Jonas Arnklint</td>
                            <td class="born">1985</td>
                        </tr>
                        <tr>
                            <td class="name">Martina Elm</td>
                            <td class="born">1986</td>
                        </tr>
                        <tr>
                            <td class="name">Gustaf Lindqvist</td>
                            <td class="born">1983</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="controls">
                <button type="button" data-sort="price:asc">Sort by price (low to high)</button>
                <button type="button" data-sort="price:desc">Sort by price (high to low)</button>
                <button type="button" data-sort="name:asc">Sort by name (A-Z)</button>
                <button type="button" data-sort="name:desc">Sort by name (Z-A)</button>
            </div>
            <div class="mixitup">
                <div class="mix" data-price="14.99" data-name="Foo">
                    <div class="card">
                        <div class="card-item">
                            <div>Comp</div>
                            <div><img src="images/pds_01.jpg" alt="comp-image"></div>
                        </div>
                        <div class="card-item">アイテム2</div>
                        <div class="card-item">アイテム3</div>
                        <div class="card-item">アイテム4</div>
                        <div class="card-item">アイテム5</div>
                        <div class="card-item">アイテム1</div>
                        <div class="card-item">アイテム2</div>
                        <div class="card-item">アイテム3</div>
                        <div class="card-item">アイテム4</div>
                        <div class="card-item">アイテム5</div>
                    </div>
                </div>
                <div class="mix" data-price="29.99" data-name="Bar">
                    <div class="card">
                        <div class="card-item">BasePasta</div>
                        <div class="card-item">アイテム2</div>
                        <div class="card-item">アイテム3</div>
                        <div class="card-item">アイテム4</div>
                        <div class="card-item">アイテム5</div>
                        <div class="card-item">アイテム1</div>
                        <div class="card-item">アイテム2</div>
                        <div class="card-item">アイテム3</div>
                        <div class="card-item">アイテム4</div>
                        <div class="card-item">アイテム5</div>
                    </div>
                </div>
                <div class="mix" data-price="59.99" data-name="Baz">
                    <div class="card">
                        <div class="card-item">soylent</div>
                        <div class="card-item">アイテム2</div>
                        <div class="card-item">アイテム3</div>
                        <div class="card-item">アイテム4</div>
                        <div class="card-item">アイテム5</div>
                        <div class="card-item">アイテム1</div>
                        <div class="card-item">アイテム2</div>
                        <div class="card-item">アイテム3</div>
                        <div class="card-item">アイテム4</div>
                        <div class="card-item">アイテム5</div>
                    </div>
                </div>
            </div>
            
Follow our [Getting Started](https://sourcethemes.com/academic/docs/get-started/) and [Page Builder](https://sourcethemes.com/academic/docs/widgets/) guides to easily personalize the template and then [add your own content](https://sourcethemes.com/academic/docs/managing-content/).

For inspiration, check out [the Markdown files](https://sourcethemes.com/academic/docs/install/#demo-content) which power the [personal demo](https://academic-demo.netlify.com/). The easiest way to publish your new site to the internet is with [Netlify](https://sourcethemes.com/academic/docs/deployment/).

- [View the documentation](https://sourcethemes.com/academic/docs/)
- [Ask a question](http://discuss.gohugo.io/)
- [Request a feature or report a bug](https://github.com/gcushen/hugo-academic/issues)
- Updating? View the [Update Guide](https://sourcethemes.com/academic/docs/update/) and [Release Notes](https://sourcethemes.com/academic/updates/)
- Support development of Academic:
  - [Donate a coffee](https://paypal.me/cushen)
  - [Become a backer on Patreon](https://www.patreon.com/cushen)
  - [Decorate your laptop or journal with an Academic sticker](https://www.redbubble.com/people/neutreno/works/34387919-academic)
  - [Wear the T-shirt](https://academic.threadless.com/)

{{% alert note %}}
This homepage section is an example of adding [elements](https://sourcethemes.com/academic/docs/writing-markdown-latex/) to the [*Blank* widget](https://sourcethemes.com/academic/docs/widgets/).

Backgrounds can be applied to any section. Here, the *background* option is set give a *color gradient*.

**To remove this section, delete `content/home/demo.md`.**
{{% /alert %}}
