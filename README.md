# fontInfo

Extracts metadata from a ttf file. Based on https://github.com/trevordixon/ttfinfo which was Ported from PHP at http://stackoverflow.com/questions/5668901/php-how-to-read-title-of-font-from-ttf-file.

Use like:

    var ttfInfo = require('fontInfo')
    console.log(ttfInfo('path/to/font.ttf'));
