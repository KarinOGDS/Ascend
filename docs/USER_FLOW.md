# USER_FLOW.md

# Ascend User Flow

## Purpose

This document defines the complete experience of a workout session.

Instead of describing technical implementation, it focuses on how users interact with Ascend and how the application responds to every action.

---

# Core Philosophy

Every interaction should make the user feel that progress has been earned.

Users should never feel like they are filling forms.

They should feel like they are progressing through a mission.

---

# Complete Workout Flow

Dashboard

↓

Select Muscle

↓

Muscle Module

↓

Select Exercise

↓

Exercise Module

↓

Complete Sets

↓

Exercise Complete

↓

Back to Muscle Module

↓

Finish Workout

↓

Workout Summary

↓

Dashboard

---

# Dashboard

## Goal

Help the user decide what to train.

## User Actions

• Select a muscle.

• Review current progress.

• View workout statistics.

## System Response

Selecting a Muscle Card starts the Context Transition animation.

The selected card expands until it becomes the active Muscle Module.

---

# Muscle Module

## Goal

Allow the user to choose which exercise to perform.

## Visible Information

Muscle Name

Muscle Rank

Exercise List

Completed Exercises

Add Exercise

## User Actions

Select an exercise.

Return to Dashboard.

## System Response

Selecting an exercise opens the Exercise Module using the same Context Transition philosophy.

---

# Exercise Module

## Goal

Guide the user through one exercise.

## Visible Information

Exercise Name

Exercise Rank

Mission Progress

Current Set

Weight

Repetitions

Rest Timer

## User Actions

Complete current set.

Modify weight.

Modify repetitions.

Finish exercise.

## System Response

Every completed set immediately updates:

• Mission Progress

• Exercise XP

• Muscle XP

Visual feedback is displayed after every completed set.

---

# Exercise Completion

When all sets are completed:

Display:

MISSION COMPLETE

Show earned XP.

Update exercise progress.

Return automatically to the Muscle Module.

The completed exercise is marked.

---

# Muscle Completion

When every exercise inside the Muscle Module has been completed:

Display:

CHEST COMPLETE

Exercises Completed

XP Earned

Muscle Progress

Enable:

Finish Workout

---

# Workout Summary

Display:

Exercises Completed

Sets Completed

Volume Lifted

Workout Duration

XP Earned

Muscle Progress

Level Progress

If the user levels up:

Display the Level Up animation.

---

# Return to Dashboard

After finishing the summary:

Return to the Dashboard.

The Hero Panel, Dashboard and Muscle Cards should immediately reflect the new progress.

---

# Context Transition

Every navigation inside Ascend follows the same interaction pattern.

Immediate Feedback

↓

Expansion Animation

↓

Content Transition

↓

New Context

Closing any module performs the reverse animation.

Users never feel that a new page has been opened.

Instead, they feel that the current context evolved into a new one.

---

# Feedback Loop

Every user action generates immediate feedback.

Selecting Muscle

↓

Context Transition

Completing Set

↓

Progress Update

Completing Exercise

↓

Mission Complete

Completing Workout

↓

Workout Summary

Level Up

↓

Progress Celebration

---

# Product Principles

Every workout must feel meaningful.

Progress should always be visible.

Animations communicate state changes.

Navigation preserves context.

Users should always know what to do next.

Every interaction should reinforce discipline and consistency.