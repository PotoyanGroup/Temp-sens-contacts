# Temp-sens-contacts

This repository hosts all the python scripts needed for reproducing plots in the manuscipt "Temperature-Sensitive Contacts in Disordered Loops Tune Enzyme I Activity"
by Daniel Burns, Aayushi Singh, Vincenzo Venditti, Davit A Potoyan; Proc Nat Acad Sci (2022)

## Instructions

ContactAnalysis contains classes and functions to explore contact data with pandas dataframes

Generate your contact data using getcontacts: https://github.com/getcontacts/getcontacts

Produce a dictionary from these contact frequency files with ContactFrequencies.make_contact_frequency_dictionary 

The dictionary can be converted to a dataframe and then provided to ContactFrequencies.ContactFrequencies where you can more easily analyse the data.

contacts_to_pymol_v2 has a number of functions to help visualize the contacts.

This is a work in progress.
