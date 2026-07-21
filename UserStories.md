User Stories:

Your page should contain a main element with the class newspaper-layout.
The .newspaper-layout should include a header with the class title containing an h1 to display the newspaper's name.
The .newspaper-layout should include an article with the class feature-article for the main news article.
The .feature-article should include an h2 element for the article title followed by a p element for the article content.
You should add three more article elements for smaller articles, with classes small-article1, small-article2, and small-article3.
Each of the smaller articles should include an h3 element for the article title followed by a p element for the article content.
The .newspaper-layout should include an article element with the class secondary-article for an additional news section.
The .secondary-article should include an h2 element for the article title followed by a p element for the article content.
The .newspaper-layout should include a figure with the class cover-image to display an image that represents the newspaper's content.
The elements with the classes title, feature-article, secondary-article, cover-image, small-article1, small-article2, and small-article3 should have a grid-area property set to the same class name.
Your .newspaper-layout should use CSS Grid with a grid-template-areas property to define the arrangement of sections:
The .title should span across the top row.
The .feature-article should span two columns in the second row, with the .cover-image in the third column.
The .secondary-article should span two columns in the third row, with the .cover-image in the third column.
The three small articles should appear in the fourth row.
The .newspaper-layout should have a grid-template-columns property that divides the space into three equal columns.
You should set the .newspaper-layout's grid-template-rows property to auto for the first row and divide the remaining space into equal parts for the other rows.
You should add a gap between grid items.
Ensure that the image inside .cover-image fits within the designated space by setting its max-width to 100%.

Tests:
Waiting:1. You should have a main element.
Waiting:2. Your main element should have a class of newspaper-layout.
Waiting:3. You should have a header element with the class of title within your .newspaper-layout element.
Waiting:4. Your header element should contain an h1 element.
Waiting:5. Your .title element should contain some text.
Waiting:6. You should have an article element for each article with classes feature-article, small-article1, small-article2, small-article3, and secondary-article, respectively.
Waiting:7. The .feature-article should include an h2 element followed by a p element.
Waiting:8. .small-article1, .small-article2, and .small-article3 should include an h3 element followed by a p element.
Waiting:9. The .secondary-article should include an h2 element followed by a p element.
Waiting:10. You should have a figure element with the class of cover-image within your .newspaper-layout.
Waiting:11. Your .cover-image should contain an img element.
Waiting:12. The display property of the .newspaper-layout element should be set to grid.
Waiting:13. Your .newspaper-layout element should have a grid-template-areas property with title spanning all three columns of the first row.
Waiting:14. The second row of the grid template should contain a feature-article spanning two columns and a cover-image.
Waiting:15. The third row of the grid template should contain a secondary-article spanning two columns and a cover-image.
Waiting:16. The fourth row of the grid template should contain small-article1, small-article2, and small-article3.
Waiting:17. Your .newspaper-layout selector should use the grid-template-columns property to divide the space into three equal parts. Remember you can use either the repeat function or manually define each fractional unit.
Waiting:18. Your .newspaper-layout selector should have a grid-template-rows property set to auto 1fr 1fr 1fr.
Waiting:19. You should add a gap between grid items.
Waiting:20. .title should have a grid-area of title.
Waiting:21. .feature-article should have a grid-area of feature-article.
Waiting:22. .cover-image should have a grid-area of cover-image.
Waiting:23. .secondary-article should have a grid-area of secondary-article.
Waiting:24. .small-article1 should have a grid-area of small-article1.
Waiting:25. .small-article2 should have a grid-area of small-article2.
Waiting:26. .small-article3 should have a grid-area of small-article3.
Waiting:27. The img inside .cover-image should have a max-width of 100%.