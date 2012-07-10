# Proportional Grids

Don't think widths, think proportions. A dead simple method of creating responsive fluid grids with fixed gutters. Use classes to set the proportions you want your grid to take at which breakpoint.

Supports nested grids and requires no `class="first"` or `:first-child` nonsense. Even works in IE7

**Check out the demo here: http://builtbyboon.com/posed/Proportional-Grids/**

## How it works

Grids are used by proportion e.g. one half, one third, two thirds etc.

Classes are used on your column to determine which proportion it takes at which breakpoint.

## A basic grid setup: ##

`<div class="grid-wrap">
    <div class="grid-col mq1-col-one-half mq2-col-two-thirds">
        <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
    </div>
    <div class="grid-col mq1-col-one-half mq2-col-one-third">
        <p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
    </div>
</div>`

Each `grid-col` starts of as a single column (on small screens / mobile). `mq1-col-one-half` means that column becomes one-half at breakpoint / media query 1. `mq2-col-two-thirds` means the column becomes two-thirds at breakpoint / media query 2.
