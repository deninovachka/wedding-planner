# Wedding Planner

## Project Overview

Wedding Planner is a web application designed to help couples plan and organise their wedding in one place.

The application brings together essential wedding planning activities, including task management, budget tracking, calendar organisation, guest management, supplier management and wedding day scheduling.

## Target Users

The primary users are couples who are organising their own wedding and need a simple way to manage preparations, expenses, guests and important dates.

## Problem Statement

Planning a wedding involves many tasks, deadlines, expenses and people. Managing this information across separate notes, spreadsheets and calendars can be time-consuming and confusing.

Wedding Planner aims to centralise this information and help users stay organised throughout the planning process.

## Core Features

- Create and manage a wedding plan
- Manage wedding preparation tasks
- Set and monitor a wedding budget
- Organise wedding dates and events
- Manage the guest list
- Keep track of wedding suppliers
- Monitor wedding planning progress
- View a wedding dashboard
- Record wedding expenses
- Create a wedding day schedule

## Project Management

The project is managed using Jira and follows the Scrum framework. Work is organised into Epics, Stories, Tasks, Bugs and Subtasks, with Stories estimated using Story Points and distributed across two sprints.

## Project Status

This repository is being developed as part of a software processes coursework project.

## Baseline Story

**SCRUM-7 – Create Wedding Plan**

This story is the baseline for the Wedding Planner project. It represents the core functionality that allows a couple to create a wedding plan and start organising their wedding. It is estimated at 3 Story Points.

## Story: Create Wedding Plan

**Jira issue:** SCRUM-7

**User story:** As a couple planning a wedding, I want to create a wedding plan so that I can organise the main details of our wedding in one place.

**Acceptance criteria:**
- The user can enter the wedding name or title.
- The user can enter the wedding date and location.
- The user can save the wedding plan details.
- The saved details can be viewed again.

**Estimate:** 3 Story Points.

**Baseline story:** This story establishes the starting point for the core Wedding Planner functionality.

### SCRUM-8 — Manage Wedding Tasks

**User story:** As a couple planning a wedding, I want to manage wedding preparation tasks so that I can keep track of the work that needs to be completed.

**Acceptance criteria:**
- The user can add wedding preparation tasks.
- The user can view the list of tasks.
- The user can update task details.
- The user can mark tasks as completed.

### SCRUM-9 — Manage Wedding Budget

**User story:** As a couple planning a wedding, I want to manage my wedding budget so that I can monitor planned costs and avoid overspending.

**Acceptance criteria:**
- The user can set a total wedding budget.
- The user can record planned costs.
- The user can view the budget and recorded costs.
- The user can compare costs against the available budget.

### SCRUM-10 — Manage Wedding Calendar

**User story:** As a couple planning a wedding, I want to organise wedding dates and events in a calendar so that I can keep track of important deadlines and appointments.

**Acceptance criteria:**
- The user can record important wedding dates.
- The user can view upcoming events and deadlines.
- The user can update event details.
- The calendar displays the scheduled dates clearly.

## Development Workflow

Each development task is linked to a Jira work item. Branches are created for individual tasks, changes are committed with the relevant Jira key, and pull requests are used to merge changes into the main branch.
## Testing Approach

The core Wedding Planner features will be checked against their expected behaviour.

- Verify that a wedding plan can be created and saved.
- Check that wedding tasks can be added and displayed.
- Verify that budget totals match recorded expenses.
- Check that the guest count matches the guest list.
- Verify that wedding dates and the day schedule are displayed correctly.

Testing results and identified defects should be documented in Jira.

## Jira and GitHub Integration

The Jira project is connected to the GitHub repository to link development work with Jira issues.

- Branches use their corresponding Jira issue keys.
- Commit messages include the Jira issue key.
- Pull requests include the Jira issue key in their titles.
- Merged pull requests are visible in the Jira issue development panel.
- Changes are merged into `main` through pull requests.

## Bug: Wedding Budget Calculation

**Jira issue:** SCRUM-20

**Problem:** The total wedding budget may be calculated incorrectly.

**Expected behaviour:** The displayed total should equal the sum of all recorded wedding expenses.

**Test cases:**
- Check the total when no expenses have been added.
- Add one expense and verify the total.
- Add multiple expenses and verify their sum.
- Edit or remove an expense and check that the total updates correctly.

- ## Bug: Wedding Guest Count

**Jira issue:** SCRUM-21

**Problem:** The displayed guest count may not match the guest list.

**Expected behaviour:** The total guest count should match the number of guests recorded in the wedding guest list.

**Test cases:**
- Check the count when the guest list is empty.
- Add one guest and verify the count.
- Add multiple guests and compare the count with the list.
- Remove a guest and verify that the count updates correctly.

## Bug: Wedding Task Order

**Jira issue:** SCRUM-23

**Problem:** Wedding tasks may be displayed in the wrong order.

**Expected behaviour:** Wedding tasks should be displayed in the order defined by their scheduled dates or selected sorting criteria.

**Test cases:**
- Add tasks with different scheduled dates and verify their order.
- Check that tasks with earlier dates appear before later tasks when sorting by date.
- Change a task's scheduled date and verify that the order updates.
- Check that tasks remain correctly ordered after refreshing the view.
