EvaBootstrap
============

EvaBootstrap is a css framework based on Twitter Bootstrap (TB), but removed invasive from TB. Which means you could use EvaBootstrap in any of your exists project, EvaBootstrap will NOT CHANGE your default css styles.

EvaBootstrap is core front-end part for project [EvaEngine](https://github.com/AlloVince/eva-engine).

Differece from Twitter Bootstrap
--------------------------------

Technically, EvaBootstrap added some namespaces to Twitter Bootstrap default style, so the usage is also changed a little bit:

###Typography


Add class .typo to typography container:


Twitter Bootstrap way:

    <p><small>This line of text is meant to be treated as fine print.</small></p>

EvaBootstrap way:

    <div class="typo">
    <p><small>This line of text is meant to be treated as fine print.</small></p>
    </div>

###Form

Add class .form to form

Twitter Bootstrap way:

    <form>
    <fieldset>
    ...
    </fieldset>
    </form>

EvaBootstrap way:

    <form class="form">
    <fieldset>
    ...
    </fieldset>
    </form>

New Features
-----------

###Chinese Typography Style

Thanks to project [typo.css](https://github.com/sofish/typo.css), you could add class .typocn to any container to get better typography style for Chinese.

###High Level CSS reset

###New LESS functions for quick css generate

###Percent grid system

###3 columns layout


Suggestions
--------------

Contact AlloVince by blog : http://avnpc.com/
