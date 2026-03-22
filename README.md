# Important Links Manager

A simple personal web app to store and manage important links, notes, and code snippets in one place.

## Live Demo

[Open Website](https://priyanshusinha-a.github.io/Courses/)

## Overview

Important Links Manager is a lightweight browser-based tool made for personal use. It helps organize useful links, short descriptions, and notes inside a clean card-based interface. The project is simple, fast, and works without any backend or database.

This website is useful for keeping all important resources in one place, such as course links, study materials, tools, websites, and short notes.

## Features

- Add new important links and notes
- Edit saved entries
- Delete single entries
- Clear all entries
- Search by title, description, code, or link
- Export saved data as a JSON backup
- Import data from a JSON backup file
- Theme selection for better UI experience
- Clean and responsive card-based design

## Technologies Used

- HTML
- CSS
- JavaScript

## How It Works

This project stores data in the browser using **localStorage**.

That means:

- Data is saved only in the user's browser
- No backend server is used
- No database is required
- Other visitors cannot see your personal saved entries
- If browser storage is cleared, saved data may be removed unless exported

## Privacy Note

This project is designed mainly for **personal use**.

The data entered into the website is stored only in the browser local storage of that user. It is not stored publicly in the hosted page itself. However, if someone uses the same device and same browser profile, they may be able to access that saved data.

For safety, do not store passwords, API keys, or highly confidential secrets in this app.

## Usage

1. Open the website
2. Click **Add New**
3. Enter the title, description, code, and link
4. Save the entry
5. Use **Search** to quickly find saved data
6. Use **Edit** to update entries
7. Use **Delete** to remove a single entry
8. Use **Clear All** to remove all current browser-saved entries
9. Use **Export** to back up your data
10. Use **Import** to restore data

## Project Purpose

The main purpose of this project is to store and update important things in one place. It can be used for:

- useful websites
- course links
- project resources
- code snippets
- personal notes
- tool collections

## File Structure

```bash
Courses/
│── index.html
