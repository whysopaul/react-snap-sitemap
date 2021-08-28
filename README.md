# React Snap Sitemap

A companion package for [react-snap](https://github.com/stereobooster/react-snap).

This package allows you to generate a sitemap.xml based off the created directories and files produced by react-snap.

## Installation

`npm install -D @alex-drocks/react-snap-sitemap`

## Usage

Add `&& react-snap-sitemap --base-url=http://example.com/` to the end of your postBuild script after you've the `react-snap` command.

To blacklist specific urls, add them with `--black-list={url},{url2},...`

You can also add `--change-frequency=always|daily|weekly|monthly|yearly|never`.

If you need trailing slashes at the end of your URLs add `--add-slash=true`
