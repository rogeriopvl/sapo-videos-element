# &lt;sapo-videos&gt;

This is a web component for embedding videos from [Sapo Vídeos](http://videos.sapo.pt).

Here's a [live demo](http://rogeriopvl.github.io/sapo-videos-element).

## Install

    bower install sapo-videos-element

## Usage

To use this component just add the following markup to your HTML:

    <sapo-video url="http://videos.sapo.pt/vz0UeKVkl92vQ2bDhIY"></sapo-video>

This will place the video embed inside the shadow-root of the element. If you wish to style it or whatever, you can pass a selector as the container for the embed:

    <sapo-videos container="#video-container" url="http://videos.sapo.pt/vz0UeKVkl92vQ2bDhIYl"></sapo-videos>

    <div id="video-container"></div>

### Attributes
* `url` - The url to the video (from Sapo Videos) to embed
* `width` - The width of the video (optional)
* `height` - The height of the video (optional)
* `hd` - Set quality to HD if video has it (optional)
* `container` - A selector to an element that will contain the embed of the video (optional)

## LICENSE

MIT License
