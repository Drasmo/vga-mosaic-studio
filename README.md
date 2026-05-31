# VGA Mosaic Studio

A portable, installation-free Mosaic Studio that runs directly in your web browser.

VGA Mosaic Studio is a lightweight, all-in-one tool designed to turn any photo into an interactive mosaic, composed of images from your own collections. Whether you want to use holiday photos, work project screenshots, or event images, this tool helps you organize and create art without the need for complex software or installations.

## Core Philosophy: "It Just Works"

The goal of this project is simplicity. No complex software suites, no cloud uploads, and no installation wizards.

* **Browser-Native:** Runs entirely within your web browser.
* **Installation-Free:** Simply download the file and open it.
* **Portable:** Everything you need is contained within the studio or the project exports it generates.

## Features

### 🎨 Paint Factory (Database Builder)
Easily categorize thousands of photos into a 256-color VGA palette. The system analyzes the "Redmean" color of your images and organizes them automatically.

### 🖼️ Schilder Studio (Mosaic Configurator)
Build interactive mosaics with real-time preview.
* Adjust grid resolution and tile sizes effortlessly.
* Smart system for handling missing colors.

### 💾 Dual Export Options
* **HTML Project:** Exports a fully interactive, portable website that you can share or host locally.
* **JPG Export:** Generates a high-resolution, print-ready JPEG of your creation.

### 🌐 Multi-Language Support
Switch seamlessly between Dutch, English, German, and French.

## How to use

1. **Start:** Open `vga_mozaiek_studio.html` in any modern web browser.
2. **Paint Factory:** Import your photos and define a folder to serve as your "paint database".
3. **Schilder Studio:** Select a target image, choose your database, and configure your mosaic settings (resolution and tile size).
4. **Result:** Build your masterpiece and export it as an interactive web app or a high-resolution image.

## Why this approach?

By using the browser's built-in file system access (`showDirectoryPicker`), this tool achieves performance levels similar to desktop software while maintaining the ease of use of a webpage. You don't need a backend server or a high-end setup; your computer's browser does all the heavy lifting.

## Getting Started

* Download the latest version of the HTML file.
* Open the file in Chrome, Edge, or Firefox.
* Follow the simple steps in the navigation bar to start creating.
