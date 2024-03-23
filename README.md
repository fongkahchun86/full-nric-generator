# full-nric-generator
Generate full-length NRIC with 3 digits and a letter.

Under the Singapore Personal Data Protection Commission's (PDPC) Technical Guide to NRIC Advisory guidelines, organisations using a masked NRIC have to be the last 3 digits & last letter of the user NRIC.

Source: https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Other-Guides/Technical-Guide-to-Advisory-Guidelines-on-NRIC-Numbers---260819.pdf

This project proves that with a 3-digit masked NRIC with a known birth year, we can generate 9 sets of valid NRIC. However, with 4 digits masked NRIC, we can narrow the identity to just 1 or 2 full NRIC.
