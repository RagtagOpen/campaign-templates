# campaign-templates

## Goal

Create a series of reusable, platform agnostic, website themes for use in progressive political campaigns.

## Requirements

1.  Themes should be adaptable to any CMS
2.  Themes should strive to achieve a WCAG 2.0 AAA rating where possible and _must_ achieve a WCAG 2.0 AA rating across the board
3.  Themes must provide implementations of each element in the core pattern library
4.  Themes must be responsive, built with the mobile-first principal in mind
5.  Themes must account for custom color schemes and may provide more than one to choose from
6.  Themes must follow progressive enhancement principles, i.e., JavaScript is used to enhance the experience but must not be required

## Overall Project Roadmap

1.  Create a list of required pattern library elements that each theme must include
2.  Build examples of each element in the pattern library with Patternlab.io and Bootstrap v4
3.  Build example implementations for WordPress, SquareSpace and Jekyll

## Individual Theme Roadmap

1.  Develop visual styles for each of the pattern library elements (can be static comps, live prototypes built in Patternlab, etc.)
2.  Implement the visual styles in Patternlab if they aren't already
3.  Implement the theme in WordPress, SquareSpace, Jekyll, etc.

Each CMS implementation should live in it's own GitHub repo and be able to be included via package managers where appropriate (https://wpackagist.org/, https://rubygems.org/). This repo will link to the various implementations.
