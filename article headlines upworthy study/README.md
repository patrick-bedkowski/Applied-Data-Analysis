<h1>Article headlines analysis - Upworthy study</h1>

<h3>Context</h3>

In this homework, we will analyze data from A/B tests of headlines conducted by Upworthy from January 2013 to April 2015 to study whether the language used in the headline determines the number of people that will read the associated news piece. The homework contains four tasks: in task 1, we will process the data; in task 2, we will extract meaningful signals from the data; in task 3, we will test whether the language of headlines impacts their success; and in task 4, we will explore the heterogeneity of this effects (e.g., does it vary through time?).

<h3>Data</h3>

| Column name          | Description                                                                                                                                                                                       |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| created_at           | Time the package was created (timezone unknown)                                                                                                                                                   |
| test_week            | Week the package was created, a variable constructed by the archive creators for stratified random sampling                                                                                       |
| clickability_test_id | The test ID. Viewers were randomly assigned to packages with the same test ID                                                                                                                     |
| impressions          | The number of viewers who were assigned to this package. The total number of participants for a given test is the sum of impressions for all packages that share the same clickability_test_id    |
| headline             | The headline being tested                                                                                                                                                                         |
| eyecatcher_id        | Image ID. Image files are not available. Packages that shared the same image have the same eyecatcher_id                                                                                          |
| clicks               | The number of viewers (impressions) that clicked on the package. The clickrate for a given package is the number of clicks divided by the number of impressions                                   |
| excerpt              | Article excerpt                                                                                                                                                                                   |
| lede                 | The opening sentence or paragraph of the story                                                                                                                                                    |
| slug                 | Internal name for the web address                                                                                                                                                                 |
| share_text           | Summary for display on social media when the article is shared. This was not shown in tests, since tests were conducted on the Upworthy website                                                   |
| square               | When used, part of the same social media sharing suggestion as the share text                                                                                                                     |
| significance         | NOT an estimate of statistical significance; a complex, inconsistent calculation that compared the clicks on a package to the clicks on all previous packages that were fielded on the same pages |
| first_place          | Along with significance, shown to editors to guide decisions about what test to choose                                                                                                            |
| winner               | Whether a package was selected by editors to be used on the Upworthy site after the test                                                                                                          |
| updated_at           | The last time the package was updated in the Upworthy system                                                                                                                                      |


<h3>Contributors</h3>

<ul>
    <li>
        <a href="https://github.com/andreeanica16">andreeanica16</a>
    </li>
    <li>
        <a href="https://github.com/EpureRares">EpureRares</a>
    </li>
    <li>
        <a href="https://github.com/maximrepidgey">maximrepidgey</a>
    </li>
</ul>
