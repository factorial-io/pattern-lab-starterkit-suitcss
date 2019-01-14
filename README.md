# StarterKit for SUIT CSS

The StarterKit is meant to be used as a kitchen sink for SUIT CSS projects.

## Requirements

The SUIT CSS StarterKit requires the following PatternEngine:

* `pattern-lab/patternengine-twig`: [documentation](https://github.com/pattern-lab/patternengine-php-twig#twig-patternengine-for-pattern-lab), [GitHub](https://github.com/pattern-lab/patternengine-php-twig), [Packagist](https://packagist.org/packages/pattern-lab/patternengine-twig)

## Install

This StarterKit can be installed via one of the following commands:

    php core/console --starterkit --init
    php core/console --starterkit --install factorial-io/pattern-lab-starterkit-suitcss

and to download npm packages run

    yarn add suitcss-base suitcss-components-arrange suitcss-components-button suitcss-components-flex-embed suitcss-components-grid suitcss-components-test suitcss-utils-after suitcss-utils-align suitcss-utils-before suitcss-utils-display suitcss-utils-flex suitcss-utils-layout suitcss-utils-link suitcss-utils-position suitcss-utils-size suitcss-utils-text

It is recommended that you **do not** install this StarterKit as a dependency for your Pattern Lab project via Composer.

## Edit Files

After installation the files for this StarterKit can be found in `source/`.
