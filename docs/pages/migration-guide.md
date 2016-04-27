---
title: Foundation 6 Migration Guide
description: This guide describes the changes required to migrate a Foundation for Sites project from version 5 to 6.
---

## Getting Started

This guide describes the changes required to migrate a Foundation for Sites project from version 5 to 6.

### Should you update?

First off, it’s important to ask yourself why you want to upgrade an existing Foundation 5 site to Foundation 6. Any migration will take time and effort. Whether it’s the A11Y compatibility or the super light codebase, you’ll want to make sure those benefits outweigh the time and effort to upgrade. After all, thousands of successful sites are still on older versions of Foundation, including version [4](http://www.newbalance.com/), [3](https://jquery.com/), and even [2](http://camps.winshape.org/)!


### Why so many changes?

We're absolutely thrilled to share with you the best version of Foundation yet. It’s faster, 50% lighter, more versatile, flexible and powerful than ever before — getting your projects from Prototype to Production. With such lofty expectations, comes lot’s of changes. We went back to the drawing board, talked to many companies, and re-evaluated how a framework helps improve your workflow without getting in your way. 

A lot has changed and that means there is no simple upgrade path. If you feel like you’re willing and able to put in the work, this migration guide will help you get your existing Foundation 5 site on version 6.

*Converting from 4 to 6 is similar for most components.*

## Overview

When migrating, the following items can be translated easily from 5 to 6:

- The standard float grid
- Forms
- Visibility
- Typography
- Text helper classes
- Button class
- Label
- Table
- Progress Bar
- Tooltip
- Flex Video
- Thumbnail
- Equalizer
- Interchange
- Pagination
- Breadcrumbs

Other areas may require more changes to work correctly, either because there are significant changes from version 5, feature gaps, or both. These areas include:

- Reveal Modal
- Media Queries (Sass)
- Navigation
- Dropdown
- Alert
- Magellan
- Switch
- Off-canvas

What’s new that you might want to use:

- Flex Grid
- Sticky
- Toggler
- Close
- Media Object
- Orbit

What’s not in F6 that was in F5:

- Pricing Tables (will be available in [Building Blocks]())
- Joyride (version 3 to be added soon!)

The new menu component replaces many separate components in Foundation 5. 

- Top Bar
- Side Nav
- Inline List
- Icon Bar
- Sub Nav

## Gulp and Bower

Foundation 5 used the Grunt task runner and Foundation 6 uses Gulp. We'll point out any differences you need to know about the versions.

## Dependencies

Good news: Foundation 6 has fewer dependencies than prior versions. We’ll list out the dependencies, and what is no longer needed from Foundation 5.

Foundation 6 Dependencies
- jQuery (v2.1.4)
- what-input.js
- Motion UI

In Foundation 6, you no longer need:
- Modernizr
- Fastclick
- jQuery.placeholder
- Normalize (bundled into codebase already)
- jQuery Cookie

With the launch the of Foundation 6, we released a new CLI that requires fewer dependencies and installs all versions of Foundation. It’s a win-win!

CLI Dependencies
- Git
- Node
- Bower

## Global



## Components

We'll call out any HTML, Sass, and JS differences between the versions here. Each component will have a HTML, Sass, and JS section to describe specific changes. 

#### HTML Markup

Any markup changes between versions will be listed for each component in the Component -> HTML sections below. Foundation 6 will have more accessibility markup and some of the classes have changes to create more consistent naming.

#### Sass

Class names, styling differences, mixins, and variables will be discussed in the Sass section for each component.

#### JS

We'll cover differences in setup, initialization, and settings in the JS section of each component.




















#### HTML Markup



#### Sass


#### JS

JS
- initialization
  - reflow
  - init after page loads
  - AJAX (if applicable)
  - init after event (if applicable)
- settings
    - data attributes
    - data-options
    - JS options

Files to load individually

### Requires MotionUI

## Build System

## Accessibility

## Contribute




