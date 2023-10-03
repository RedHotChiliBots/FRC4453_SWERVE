# MAXSwerve Java Template v2023.1

See [the online changelog](https://github.com/RedHotChiliBots/FRC4453_SWERVE/blob/main/CHANGELOG.md) for information about updates to this project.

## Description

FRC 4453 2024 swerve drivetrain

This project is built on Swerve Drive Specialties Mk4i modules, each with two SparkMax controllers and two NEOs, one for Drive motor and one for Turn motor.  The absolute encoder is the CTRE Mag Encoder custom wired to a Rev Encoder Breakout board attached to the Data Port on the Turn SparkMax.

The absolute encoders are calibrated by setting the zero offset using the Rev Hardware Client.  Zero is set the same for all modules to allow module replacement. 

## Prerequisites

* SPARK MAX Firmware v1.6.2 - Adds features that are required for swerve
* REVLib v2023.1.2 - Includes APIs for the new firmware features

## Configuration

It is possible that this project will not work for your robot right out of the box. Various things like the CAN IDs, PIDF gains, chassis configuration, etc. must be determined for your own robot!

These values can be adjusted in the `Constants.java` file.
