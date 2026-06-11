## Gmail Compose Feature - Manual & BDD Test Suite


Project Overview
	This repository contains a comprehensive manual test artifact suite designed to validate the core functional, operational, and structural security integrity of the **Gmail Compose & Send** functionality. 

## Repository Structure
	Test_artifcats: Contains the master spreadsheet execution matrix.
  	Tab 1: Traditional Cases (15 detailed structural test cases covering functional happy paths, boundary limits, and UI responsiveness).
 	Tab 2: BDD Gherkin Scenarios (15 behavior-driven scripts mapping out edge cases, network resilience, and injection sanitization validations).

## Key Testing Methodologies Applied
	Positive & Negative Path Boundaries: Validated field limits, missing inputs, and mandatory structural flags.
	Network Resilience Simulation: Mapped graceful degradation behaviors during unexpected connection failures mid-composition.
	Security Input Sanitization: Integrated edge cases to verify client/server defense blocks against cross-site scripting (XSS) and SQL injection payloads inside text canvases.