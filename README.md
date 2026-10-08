# Accra Luxe Homes AI Lead Assistant

## Overview
An AI assistant on WhatsApp and the web that replies to property enquiries in under 60 seconds at any hour, qualifies the lead, scores it, sends the matching TikTok tour video, and hands hot leads to a human agent.

## Problem
Accra Luxe Homes receives about 50 enquiries a month, mostly rentals, through WhatsApp, TikTok, and calls. Replies take 2 to 5 hours. Agents waste minutes searching their phones for the right tour video. Leads go to faster competitors.

## Solution
A conversational AI built on Voiceflow, n8n, Supabase, Groq, and Gemini Flash. It qualifies renters and buyers, matches them to listings in Google Sheets, calculates the upfront lease total, sends the right TikTok video, logs everything, and alerts agents on Discord when a lead is hot.

## Key Features
- WhatsApp and web chat conversations
- Qualification for rent and buy
- Automatic listing and video matching
- Upfront lease total calculated by n8n, not the AI model
- Lead scoring from 0 to 100 with hot, warm, and cold tiers
- Discord alerts for hot leads within 1 minute
- English voice note transcription and screenshot understanding
- Full guardrails and human handoff with reason codes
- Supabase logging with a 90 day retention rule

## Success Metrics
- First response time: under 60 seconds
- Rental qualification handled without a human: 80 percent
- Time from qualification to video sent: under 2 minutes
- Qualified lead rate: 20 percent higher than baseline
- Hot leads reach an agent: Discord alert within 1 minute

## Out of Scope
- No legal or mortgage advice
- No price negotiation or discounts
- No payment collection
- No confirming viewing times
- No currency conversion
- No filtering by ethnicity, religion, or nationality

## Full Document
[View the full PRD here](docs/PRD.md)