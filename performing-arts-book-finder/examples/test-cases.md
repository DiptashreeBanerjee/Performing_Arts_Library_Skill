
# Performing Arts Book Finder: Test Cases

## Test 1: Basic Search

Input:
Find five books on theatre in India.

Expected:
- Country: India
- Discipline: Theatre
- Five relevant books, if verifiable
- Bibliographic information

## Test 2: Academic Search

Input:
Find five academic books on traditional dance in Japan.

Settings:
academic_only = true
traditional_arts = true
contemporary_arts = false

Expected:
Scholarly books on traditional Japanese dance.

## Test 3: Historical Search

Input:
Find books on the history of theatre in Greece.

Settings:
historical_focus = true

Expected:
Historical studies of Greek theatre.

## Test 4: Open Access Preference

Input:
Find books on puppetry in Indonesia.

Settings:
open_access_preference = true

Expected:
Prioritise books with confirmed free full-text access.

## Test 5: Verification

Input:
Find ten books on music in Nigeria.

Settings:
strict_verification = true

Expected:
Only books with corroborated core bibliographic details.

## Test 6: Multiple Disciplines

Input:
Find books on theatre, dance, and music in India.

Expected:
Separate recommendations by discipline.
