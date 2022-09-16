# Temp-sens-contacts

This repository hosts all the python scripts needed for reproducing plots in the manuscipt "Temperature-Sensitive Contacts in Disordered Loops Tune Enzyme I Activity"
by Daniel Burns, Aayushi Singh, Vincenzo Venditti, Davit A Potoyan; Proc Nat Acad Sci (2022)

## Instructions for using the scripts

1. ContactAnalysis contains classes and functions to explore contact data with pandas dataframes

2. Generate your contact data using getcontacts: https://github.com/getcontacts/getcontacts

3. Produce a dictionary from these contact frequency files with ContactFrequencies.make_contact_frequency_dictionary 

4. The dictionary can be converted to a dataframe and then provided to ContactFrequencies.ContactFrequencies where you can more easily analyse the data.

5. contacts_to_pymol_v2 has a number of functions to help visualize the contacts.

> This is a work in progress.
