# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Added several attributes from typical SW report format during "AML workshop 2 - attributes"

## [0.0.8] - 2021-08-01

### Added

- New SystemUnitClassLib, with Name="SequenceElementLibrary"
- New SystemUnitClass with Name="StandardSequenceElementClass", under SequenceElementLibrary, with members:
  - Start, End, Step, Transition, Action, Condition, ParallelSynchronizationStart,
    ParallelSynchronizationEnd, AlternativeBranchStart, AlternativeBranchEnd
- New InterfaceClass with Name="NorsokSequenceFlowClass", with members:
  - SequenceFlowIn, SequenceFlowOut, SequenceFlowTimeout
- New SystemUnitClass with Name="SequenceStructure", under StructureClassLibrary
- New SystemUnitClass with Name="SequenceOffPage", under ToDestination
- New SystemUnitClass with Name="SequenceOnPage", under FromSource

### Changed

- Changed convention for XML elements without element value to self-closing syntax
  - eg, '&lt;XmlElement Attribute="Value"` /`&gt;~~&lt;/XmlElement&gt;~~'

## [0.0.7] - date unknown

### Added

- First version committed to git

[unreleased]: https://github.com/equinor/iec63131/compare/0.0.8...HEAD
[0.0.8]: https://github.com/equinor/iec63131/compare/0.0.7...0.0.8
[0.0.7]: https://github.com/equinor/iec63131/compare/128cce0...0.0.7