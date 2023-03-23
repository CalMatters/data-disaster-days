# Disaster Days Dataset

In 2019, CalMatters published an investigative series called "Disaster Days", where we explored records of school closures between 2002 and 2019 to determine what reasons bubbled up most prominently. What we found was how the crises of the 21st century were impacting students across the state who lost instructional days that in many cases were never made up. The series, reported by former CalMatters K-12 reporter Ricardo Cano, found that "every fifth student in California sent home (in 2018) at least once for a natural disaster day, a maintenance crisis day, a threatened school shooting day or some other emergency."

To compile this dataset, CalMatters requested emergency school closure incidents reported by local school districts to the state's Department of Education from the 2002-03 school year (the farthest back records of this nature went) to the 2018-19 school year. We then built a database from those forms establishing a standardized cause for closures based on what details forms provided (spoiler: some forms were more detailed than others). 

## Installation and Use

The dataset is provided as a csv file and can be imported into many tools, like Excel and Google Spreadsheets. 

## Data Dictionary

Note: We omitted reports where we couldn't completely verify the reason or number of days for the closure. This encompasses 82 out of 15,159 reports.

<table>
  <thead>
    <tr>
      <th>Field</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>school</td>
      <td>
        <p>name of the school</p>
      </td>
    </tr>
    <tr>
      <td>district</td>
      <td>
        <p>school district where school is organized under</p>
      </td>
    </tr>
    <tr>
      <td>school_year</td>
      <td>
        <p>school year of report</p>
      </td>
    </tr>
    <tr>
      <td>enrollment</td>
      <td>
        <p>enrollment for the school year</p>
      </td>
    </tr>
    <tr>
      <td>category</td>
      <td>
        <p>category for closure report, created by CalMatters</p>
      </td>
    </tr>
    <tr>
      <td>reason</td>
      <td>
        <p>reason for closure report, created by CalMatters</p>
      </td>
    </tr>
    <tr>
      <td>description</td>
      <td>
        <p>description of closure provided in report</p>
      </td>
    </tr>
    <tr>
      <td>date_description</td>
      <td>
        <p>dates in which the closure occured</p>
      </td>
    </tr>
    <tr>
      <td>year</td>
      <td>
        <p>calendar year</p>
      </td>
    </tr>
    <tr>
      <td>days</td>
      <td>
        <p>closure days from incident</p>
      </td>
    </tr>
    <tr>
      <td>cds_code</td>
      <td>
        <p>County-District-School (CDS) code for the school</p>
      </td>
    </tr>
    <tr>
      <td>county</td>
      <td>
        <p>county where school is located</p>
      </td>
    </tr>
  </tbody>
</table>

## Examples of Use

- [Disaster Days series start](https://calmatters.org/projects/school-closures-california-wildfire-outage-flood-water-electricity-guns-snow-days-disaster/)
- [Interactive database](https://disasterdays.calmatters.org/california-school-closures)

## Data Use

If you use this dataset, please mention it was collected, combined and cleaned by CalMatters. We would love to know how you used it, so feel free to [send us a message](<mailto:john@calmatters.org>) if you do. If you have any questions about this dataset, feel free to [contact us](<mailto:john@calmatters.org>) as well.

CalMatters is a nonpartisan, nonprofit journalism venture committed to explaining how California’s state Capitol works and why it matters.
