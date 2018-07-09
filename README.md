# Suffolk Libraries v2

Rationalised Suffolk Libraries website.

## Principles

- Fewer includes, more repeated, large scale modules (remove included class chains)
- Fewer layouts
- All posts stored in `_posts` folder
- Flexbox grid
- Accessible search reveal at narrow screen

## Grid

- Stacked single column by default
- Columns should have 2% margin between them, use `space-between` for margins
- x of x cols always = 100% width
- Achievable with Tachyons flexbox module

### 2 col widths

- 1 col 49%
- 2 col 100%

### 6 col widths

- 1 col 15%
- 2 col 32%
- 3 col 49%
- 4 col 66% (or two-thirds)
- 5 col 83%
- 6 col 100%

## Example syntax

`<div class="flex flew-wrap space-between">

    <div class="c-w-49 c-w-15-l">

        {{ content }}

    </div>

    <div class="c-w-49 c-w-15-l">

        {{ content }}

    </div>

    <div class="c-w-49 c-w-15-l">

        {{ content }}

    </div>

    <div class="c-w-49 c-w-15-l">

        {{ content }}

    </div>

    <div class="c-w-49 c-w-15-l">

        {{ content }}

    </div>

    <div class="c-w-49 c-w-15-l">

        {{ content }}

    </div>

</div>`

Would render a 2x3 grid up to large, and a 6x1 grid at large and above.
