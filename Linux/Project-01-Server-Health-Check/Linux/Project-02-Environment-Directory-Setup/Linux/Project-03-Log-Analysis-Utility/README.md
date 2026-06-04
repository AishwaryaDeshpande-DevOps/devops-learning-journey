# Linux Log Analysis Utility

## Objective

Analyze application log files using Linux command-line tools to quickly identify important events and troubleshoot issues.

## Platform

Utho Cloud Linux Server

## Problem Statement

Application logs are one of the primary sources of information when diagnosing failures, errors, or performance issues. This project focuses on inspecting log files using Linux commands.

## Commands Used

### Create Log File

touch app.log

### Edit Log File

vim app.log

### Display Entire Log

cat app.log

### Display First Few Lines

head app.log

### Display Last Few Lines

tail app.log

### Display Specific Number of Lines

head -n 3 app.log

tail -n 2 app.log

## Sample Log Entries

INFO Application Started

INFO Database Connected

WARNING High Memory Usage

ERROR Database Timeout

INFO Retry Connection

INFO Service Restored

## Outcome

- Created and managed log files
- Practiced log inspection techniques
- Retrieved specific log entries efficiently
- Learned basic troubleshooting workflows

## Real World Use Case

DevOps engineers regularly analyze logs to identify deployment failures, application crashes, infrastructure issues, and security incidents.
