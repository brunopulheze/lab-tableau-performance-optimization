![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Tableau Performance Optimization

In this lab, you will optimize the performance of your latest version of existing Tableau Book from the [Car insurance auto business case study](./case-study_car_insurance_company.md).

<!-- **Prerequisites:** Complete [Tableau Stories lab](../../../../Week%201/Day%204%20-%20Tableau%20Dashboarding%20and%20actions/Lab/lab_2_Tableau_story/readme.md)  with working dashboards and story points. -->

**Prerequisites:** Complete [Tableau Stories lab](https://github.com/ironhack-labs/lab-tableau-stories-1)  with working dashboards and story points.

---

## Instructions

### Part 1: Performance Analysis 

1. **Record Performance** using Run Optimizer 

### Part 2: Optimize Your Workbook 

You may use the below proposed optimization steps or come up with your own approach.

Proposed optimization steps: 

   - **Data Optimization:**

      - Hide unused fields during extract creation
      - Add filters to reduce data volume where appropriate

   - **Visualization Optimization:**
      - For sheets with 1,000+ marks: Add Top N filters or date range filters
      - Replace complex scatter plots with heat maps or summary tables
      - Remove unnecessary calculated fields

   - **Dashboard Optimization:**
      - Replace global filters with dashboard actions where possible
      - Limit dashboards to 3-5 sheets maximum
      - Remove decorative elements that don't add analytical value

### Part 3: Test & Compare 
1. **Run new performance recording** following the same steps as Part 1
3. **Compare results:** Document improvement in load times

## Deliverables

- `main.txt` file with a link to your Tableau Public workbook.
- `Readme.md` file that breifly describes the approach used to optimize the latest Tableau Book. 

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.