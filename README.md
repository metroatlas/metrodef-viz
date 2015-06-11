# metrodef-viz

## d3
Contains the d3.js library for javascript.

## force_viz.html
A d3 script that renders data from the folder networkData into a force-directed layout visualization of county-to-county commuting networks for each of the states in the continental U.S.

## networkData
Contains tables of county-to-county commuting links for each of the states in the continental U.S. The links are ordered such that adding new links as one moves down the link table mirrors the process of clustering the counties hierarchically by commuting integration. For each state, there is one table for 'average linkage' hierarchical clustering and one for 'single linkage' hierarchical clustering.
