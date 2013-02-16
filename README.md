readmore-readless
=================

A jquery plugin for Read more and Read less functionality


We can achieve the Read more and Read less functionality by simple code.

          ### Initialize the plugin with no custom options
          $("#readMoreReadLess1").readMoreReadLess();

          ### Use the plugin with items in summary set to 1
          $("#readMoreReadLess2").readMoreReadLess({
              itemInSummary: 1
          });

          ### Use the plugin with custom text for Read more and Read less.
          $("#readMoreReadLess3").readMoreReadLess({
              readMoreText: 'Show more items ...',
              readLessText: 'Show fewer items ...',
              readMoreClass:'button',
              readLessClass:'button'
          });
