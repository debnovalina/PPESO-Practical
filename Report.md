Impact of canopy properties on bottom of the atmosphere (BOA) reflectance.

1. Fixing the LAI, study the relation between leaf chlorophyll content and the spectral reflectance in the VNIR (0.4~\mu m to 2.5~\mu m). Which of the Sentinel-2 MSI bands is most sensitive to chlorophyll content?
    Bands B5 to B8 show the greatest sensitivity to chlorophyll variations. Chlorophyll strongly absorbs light, particularly in the blue and red regions. Variations in chlorophyll content significantly affect reflectance in this range, particularly in the red band.

2. Fixing the chlorophyll content to a reasonable (typical?) value, study now the relation between LAI and the spectral reflectance.
    A typical value for leaf chlorophyll content in healthy vegetation is 40~\mu/cm2.
    - For visible bands (400-700 nm), the reflectance decreases with increasing LAI.
    - For NIR bands (700-1300 nm), the reflectance increases with increasing LAI. In the NIR, leaves have higher reflectance due to internal leaf structure and cell scattering.
    - For shortwave infrared bands (1300-2500 nm), the reflectance decreases with increasing LAI. The reflectance in the SWIR is lower than in the NIR as more vegetation layers contribute to scattering and due to the strong absorption of water in the SWIR region.

3. Something highly important is water stress (shortage of water). Changing the leaf water content, explore which wavelengths (and which MSI band) is most sensitive to water-stress.
    Band 11 (1610 nm) and Band 12 (2190 nm) are most sensitive to water stress. Water absorbs light in the NIR and SWIR regions, leading to a decrease in reflectance in these bands. 

4. As discussed during the lecture, the NDVI is a very popular index used to monitor vegetation. Explore the relation (e.g. can we find a regression curve?) between NDVI (for example using the B8 and B4 MSI bands) and LAI. What are the other main parameters impacting the NDVI?
   The NDVI is sensitive to vegetation density. Higher NDVI values imply denser vegetation (higher LAI).
   Other parameters impacting the NDVI include:
   - Leaf chlorophyll content (cab): impacts the red band reflectance.
   - Soil reflectance (rsoil): influences NDVI when vegetation cover is sparse.
   - Leaf water content (cw): has small effects, particularly in RED and NIR regions.
   - Canopy structure (LAI and leaf angle): strong influence, particularly at low to moderate LAI levels.
   
