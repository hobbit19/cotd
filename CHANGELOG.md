# Change Log
All notable changes to this project will be documented in this file.
 
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

### Added

- Add a tkinter GUI for a user-friendly experience
- Add active KeyListener to halt program execution
- Add grayscale option for *TemplateMatchLocator*
- Add other circle detection algorithms, current version only implements value difference

### Changed

- Refactor code to meet MVC standards in GUI implementation

## [0.4.1] - Codename: "Milkmocha" - 2020-07-21

### Changed

- Change *algorithm* parameter to *bait*
- Modify bait style implementation in main loop
 
## [0.4.0] - Codename: "Milkmocha" - 2020-07-22
 
### Added

- Add a **CHANGELOG.md**
- Add multiple template matching for *bait* choice
- Add *MinMaxRadiusException*
 
### Changed

- Change **imageprocessor.py** *ObjectDetector* class from using Strategy pattern to Factory pattern
- Rework **imageprocessor.py** to implement Factory pattern to reduce complexity
- Rework **cotd.py** for the introduction of Factory pattern to main file
- Change class name *InvalidWindowCoordinates* to *InvalidWindowCoordinatesException*
- Change **background.jpg** to **catch_region.jpg**

### Fixed

- Fix late outputs to console in executable
- Fix deadlock timer in main loop
 
### Removed

- Remove unmaintained and unused circle detection algorithms
- Remove *algorithm* parameter in program
- Remove unused images in **/res**
- Remove unused **/exceptions** folder

 
## [0.3.1] - Codename: "Latte" - 2020-07-20
 
### Added

- Add template matching for *broccoli bait*
 
### Changed
  
- Change *CircleDetectionAlgorithm* to *ObjectDetectionAlgorithm* for inclusion of template matching of baits
- Change *fishing rod* circle detection to more accurate template matching to prevent lapses in detection
 
### Fixed
 
- Fix *State.fishing* ending prematurely due to lapses in *fishing rod* circle detection