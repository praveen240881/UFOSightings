# UFOSightings# Custom UFO Webpage

## Project Overview
The purpose of this project is to build a UFO webpage for a hypothetical client "Dana," which has a dynamic table that allow users to filter for multiple criteria at the same time. This webpage is built with JavaScript, HTML, and CSS.

To filter the UFO sighting data, type the desired search criteria into the specified search fields. Example placeholder entires are visible in each of the fields to guide user responses and enter information in the correct format. For example, the "Enter Date" field take searches in a numbered format, such as [1/7/2010]. The table will dynamically update and return results after entering search fields. If no matches are found, the table will be empty.

### Multiple Search Criteria

![multiple_search]

This dynamic table is also able to handle multiple search criteria. In the example above, the seach criteria "circle" ordinarily returns multiple results. However, the additional "mason" search constraint reduced the results to one entry.

## Summary

Although relatively clean-looking, this webpage has room for improvement. One drawback of the current design is that it is not immediately obvious that the table is dynamically updated. Users might be expecting a button that explicitly says "Filter" or "See Results" and this new design might be confusing.

### Recommendations for Improvement

Here are two recommendations for further development:

  1. Create multiple pages for the entry results. As the total number of entries in this list increases, this webpage will become clunky and difficult to scroll thorugh so many entries. Additionally, create a button that allows the user to choose how many results are shown per page (25, 50, 100, etc.).
  2. Create sorting functions. As the number of results grow, users may want an ability to sort the results to see more relevant data. Examples include sorting by Date (Ascending/Descending) or by City Name (A to Z, Z to A). 



