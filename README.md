<h1 align="center" style="border-botom: none">
  <b>
  🐍 EIOPA RFR (Risk free curve) test 🐍
 </b>
</h1>

</br>

Every month, EIOPA releases their technical information on the risk free rate term structure that (re)insurers need to use to calculate their technical provisions. This test recalculates the risk-free curve using the parameters that are claimed to be used.

## This example
In this example, we look at the EIOPA risk free rate publication for each month starting from December 2021 onward. The publication can be found [EIOPA RFR website](https://www.eiopa.europa.eu/tools-and-data/risk-free-interest-rate-term-structures_en).

## Smith&Wilson algorithm

The implementation of the SW algorithm is a slight modification to the original OSM implementation. The original implementation can be found in different languages on the OSM's GitHub repository:
-  [Python](https://github.com/qnity/insurance_python/tree/main/smith%26wilson)
-  [Matlab](https://github.com/qnity/insurance_matlab/tree/main/smith%26wilson)
-  [JavaScript](https://github.com/qnity/insurance_javascript/tree/main/smith-wilson)

| Date                     | Repository                          |
| -------------------------| ----------------------------------- |
| 31 August 2023           | [August 2023 repository]            |
| 31 July 2023             | [July 2023 repository]              |
| 30 June 2023             | [June 2023 repository]              |
| 31 May 2023              | [May 2023 repository]               |
| 30 April 2023            | [April 2023 repository]             |
| 31 March 2023            | [March 2023 repository]             |
| 28 February 2023         | [February 2023 repository]          |
| 31 January 2023          | [January 2023 repository]           |
| 31 December 2022         | [December 2022 repository]          |
| 30 November 2022         | [November 2022 repository]          |
| 31 October 2022          | [October 2022 repository]           |
| 30 September 2022        | [September 2022 repository]         |
| 31 August 2022           | [August 2022 repository]            |
| 31 July 2022             | [July 2022 repository]              |
| 30 June 2022             | [June 2022 repository]              |
| 31 May 2022              | [May 2022 repository]               |
| 30 April 2022            | [April 2022 repository]             |
| 31 March 2022            | [March 2022 repository]             |
| 28 February 2022         | [February 2022 repository]          |
| 31 January 2022          | [Jenuary 2022 repository]           |
| 31 December 2021         | [December 2021 repository]          |

[August 2023 repository]:https://github.com/open-source-modelling/EIOPA_Monthly_RFR_check/tree/main/23_August
[July 2023 repository]:https://github.com/open-source-modelling/EIOPA_Monthly_RFR_check/tree/main/23_July
[June 2023 repository]:https://github.com/open-source-modelling/EIOPA_Monthly_RFR_check/tree/main/23_June
[May 2023 repository]:https://github.com/open-source-modelling/EIOPA_Monthly_RFR_check/tree/main/23_May
[April 2023 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/23_April
[March 2023 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/23_March
[February 2023 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/23_February
[January 2023 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/23_January
[December 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_December
[November 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_November
[October 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_October
[September 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_September
[August 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_August
[July 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_July
[June 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_June
[May 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_May
[April 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_April
[March 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_March
[February 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_February
[Jenuary 2022 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/22_January
[December 2021 repository]:https://github.com/qnity/EIOPA_Monthly_RFR_check/tree/main/21_December

Queries and suggestions; gregor@osmodelling.com
