MarketPulse Overview

MarketPulse is a PHP-based stock market analysis platform designed to fetch and analyze real-time data from the NSE (National Stock Exchange) using the Upstox API.

The platform provides live OHLC tracking, automated market scanners, and pattern-based analysis tools to help traders and analysts evaluate stock performance efficiently. It is built as a lightweight web application with secure authentication and optimized API handling for fast and reliable market insights.

Objective

The primary objective of MarketPulse is to:

Provide real-time stock market data in a simplified interface

Automate pattern-based market scanning

Assist traders in identifying potential bullish or bearish setups

Minimize API load through efficient data caching

Ensure secure access to market data through authentication

Key Features

Real-time NSE data integration

Live OHLC (Open, High, Low, Close) tracking

Automated pattern-based scanners (Open = High, Open = Low)

Early market snapshot (9:15 AM Nifty analysis)

Secure login and registration system

Instrument list management with symbol-token mapping

Lightweight data caching mechanism

Responsive and minimal user interface

System Modules

Authentication Module
User registration and login

Secure PHP session handling

Access restriction using auth guard

Market Data Module
Fetches real-time and historical data

Retrieves OHLC values for instruments

Displays structured stock information

Market Scanner Module
Identifies Open = Low (bullish indicator)

Identifies Open = High (bearish indicator)

Generates filtered stock lists

Nifty Snapshot Module
Captures early market behavior at 9:15 AM

Helps assess opening market sentiment

Instrument Management Module
Loads and maps NSE instruments

Maintains symbol-token relationships

Caching Module
Stores recent API responses temporarily

Reduces redundant API calls

Improves system performance

Main Functionalities

Secure Login & Registration

Fetch OHLC Data for Stocks

Market Pattern Scanning (O=H / O=L)

Nifty 9:15 Market Snapshot

Complete NSE Instrument List Fetching

API Data Caching

Access Protection via Authentication Guard

System Architecture (Working Concept)

User Authentication

Users log in securely using PHP sessions.

Unauthorized access to API endpoints is restricted.

API Communication

The system connects to Upstox API using a secure access token.

Requests are sent to retrieve instrument and market data.

Data Processing

JSON responses are parsed in PHP.

Data is filtered based on predefined trading logic.

Results are formatted for display.

Frontend Display

Data is presented in structured tables.

Users can navigate between dashboards and scanners.

Real-time refresh ensures updated market insights.

Performance Optimization

Frequently requested data is cached temporarily.

Cache auto-refresh ensures balance between speed and accuracy.

Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

API Provider: Upstox API

Server Environment: Apache (XAMPP)

Future Enhancements

Advanced technical indicators (RSI, MACD, Moving Averages)

Interactive stock charts with graphical visualization

Portfolio tracking module

Alert system for price movements

AI-based predictive analytics

Deployment on cloud environment

Developer Information

Project Title: MarketPulse Developed By: Dhruva D Role: Full Stack Developer Technologies: PHP, MySQL, HTML, CSS, JavaScript Year: 2025
