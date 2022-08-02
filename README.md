# Data Modeling with Apache Cassandra 

This project is part of Udacity Data Engineer Nanodegree

## Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

They'd like a data engineer to model the data by creating tables in Apache Cassandra to run queries provided by the analytics team.

## Data

**Song Dataset**: it is in the format of JSON files and each file attributes are: num_songs, artist_id, artist_latitude, artist_longitude, artist_location, artist_name, song_id, title, duration, and year.

**Log Dataset**: it is in the format of JSON files and each file attributes are: artist, auth, firstName, gender, itemInSession, lastName, length, level, location, method, page, registration, sessionId, song, status, ts, userAgent, and userId.

## Project Steps

1- Processing of the event_datafile_new.csv dataset to create a denormalized dataset

2- Modeling the data tables keeping in mind the queries needed to run

3- Loading the data into tables created in Apache Cassandra and running the queries


## How to run the project

First you need to have Python3, Jupyter Notebook and Apache Cassandra installed on your machine or VM.
