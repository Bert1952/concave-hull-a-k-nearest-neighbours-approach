For those interested in convex/concave processing:

Based on the article Adriano Moreira and Maribel Yasmina Santos i feeded the suggest pseudo code into ChatGPT and asked to build the B4j program. Well it save a lot of typework, but never worked. After that debugged the AI code and finally got it working.
Perfomance is good. Processing time ... it can be much better.
With a huge file of points (>3000) the program might give a stackoverflow.
the PointInPolygon function has some issues. Or points are outside the polygon and the function return False. Or the function returns True so a stackoverflow will be the result. Needs some attention.


