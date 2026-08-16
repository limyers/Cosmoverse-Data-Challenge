# CosmoVerse 2026 Data Challenge - Submission by Lily Myers

In this repository, I have my versions of all the juypter notebooks, my TGRB distance measurement results [(trgb_results.csv)](https://github.com/limyers/Cosmoverse-Data-Challenge/blob/main/trgb_results.csv), and a lab journal ( [View as PDF](https://github.com/limyers/Cosmoverse-Data-Challenge/blob/main/Lab_Journal.pdf) | [View as Google Doc](https://docs.google.com/document/d/1npHs0fiotWfHiDuuPpl6BteLXsuTF_w4p6OFCxnz9tU/edit?usp=sharing) ) detailing my reasoning for all 17 SN target host galaxies. 

## Summary of Results

* **Final Hubble Constant ($H_0$):** $89.8227 \pm 1.5575 \text{ km/s/Mpc}$ (derived from the unmodified `*** BEFORE ***` calibration across 11 matching SH0ES Type Ia supernova hosts, with $M_B = -18.8033 \pm 0.0368 \text{ mag}$ and $\chi^2/\text{dof} = 1.292$).
* **Methodological Findings & Systematics:**
  * **Completeness & AGB Confusion:** For more distant target galaxies with true distance moduli approaching $\mu \gtrsim 32 \text{ mag}$ (such as NGC 1309, NGC 3021, and NGC 3370), photometric incompleteness and Asymptotic Giant Branch (AGB) contamination caused the Sobel filter to lock onto apparent tips near $m_{\text{TRGB}} \approx 27.3 - 27.5 \text{ mag}$ rather than the true, fainter TRGB tip around 28.5 mag. 
  * **Distance Scale Impact:** This caused the distance moduli for those distant hosts to cap out near $\mu \approx 31.5 \text{ mag}$, systematically compressing the distance scale and ultimately achieving a very high $H_0$ measurement.
  * **Complete Documentation:** Full parameter selections, GLOESS smoothing choices ($\tau$), Sobel weighting configurations, and stability checks are detailed in my lab journal.

## Acknowledgements

Thank you to everyone who made this challenge possible! It was very fun to participate and get the chance to put what I've learned in class into practice and get my own value of $H_0$.

### Data Challenge Organizers
Siyang Li, Eleonora Di Valentino, Jackson Said 

### Challenge preparation and materials
Siyang Li, Yukei Murakami, Kayla Owens (team leads)

### Notebooks
- **TRGB distance measurement notebook** (`1_TRGB/`): Siyang Li (coordinator); algorithm contributors: Chandra Shekhar Saraf, Swayamtrupta Panda, Mahdi Najafi, Rahul Shah, Luis Escamilla, Payam Ghafari, Masoume Reyhani
- **Hubble constant notebook** (`2_hubble_constant/`): Yukei Murakami

### Data curation
Kayla Owens (coordinator); Masroor C. Pookkillath, Ayush Hazarika, Antonio Quintana, Trisha Khan, Jess Worsley, Vasiliki Karanasou, Yoelsy Leyva

---

