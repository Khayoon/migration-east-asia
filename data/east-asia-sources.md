# East Asia and Siberia: sources and interpretation

The animation combines seasonal distributions inferred from eBird observations supplied through [GBIF](https://www.gbif.org/dataset/4fa7b334-ce0d-4e88-aaae-2e0c138d049e) with explicitly illustrative summer-range supplements for three shorebirds. The following research and conservation accounts support the destination summaries shown when a species is selected, and the broad breeding regions used for those supplements. The animated dots are not the studies' tracking records.

## How seasonal ranges are drawn

The data contain 483,584 reported observations for 12 species, divided into 24 half-month periods. Sightings are smoothed and adjusted using all-bird reporting to reduce differences in observation effort. These reporting totals are not population counts. No empty smoothed periods needed to borrow another period in this build.

Nine species use these observed distributions throughout the year. Great Knot, Red-necked Stint and Far Eastern Curlew have too few Siberian breeding reports to show a useful summer distribution from sightings alone. Their May–August distributions blend the observations with broad, land-masked breeding-range illustrations supported by the accounts below. Great Knot's illustration covers northeastern Siberian uplands; Red-necked Stint's covers Arctic Siberia; Far Eastern Curlew's covers northeastern China and the Russian Far East.

The kernel centres, widths and half-month blend fractions are author-chosen illustration parameters. They are not measured occupancy, population fractions, new sightings, or precise migration dates. Their full parameters and source links are recorded under each species' `seasonalPrior` in `east-asia-birds.json`. Raw reporting counts and January–April/September–December distributions remain unchanged. Equal dots per species keep each species visible without implying relative population size.

| Species | Destination evidence |
| --- | --- |
| Arctic Warbler | [Heim et al., central Siberia–Indonesia geolocator study](https://researchprofiles.ku.dk/en/publications/from-siberia-to-indonesia-tracking-the-migration-of-the-arctic-wa/): eastern Siberia and Taiwan on autumn passage, Philippines/Indonesia in winter, Mongolia on return. One complete tracked individual, supplemented by ring recoveries. |
| Siberian Rubythroat | [Heim et al., annual-cycle tracking](https://macroecointern.dk/pdf-reprints/Heim_JO_2018.pdf): Amur-region birds connected northeast China with southern China and Indochina. |
| Yellow-breasted Bunting | [Heim et al., migration and survival study](https://pmc.ncbi.nlm.nih.gov/articles/PMC11666740/): Baikal/Amur breeding birds wintered in Southeast Asia and southern China. [Thongsuk et al., winter habitat study](https://lkcnhm.nus.edu.sg/wp-content/uploads/sites/11/2025/11/RBZ-2025-0039.pdf) describes the wider winter range, including northern India and Nepal. |
| Rustic Bunting | [Edenius et al., population research](https://www.cambridge.org/core/journals/bird-conservation-international/article/next-common-and-widespread-bunting-to-go-global-population-decline-in-the-rustic-bunting-emberiza-rustica/33DD0A30F5A84E8873388277C07C1BAF): Eurasian taiga breeding range and wintering in Japan, Korea and eastern/central China. |
| Siberian Crane | [CMS eastern-population monitoring](https://siberian-crane.cms.int/page/monitoring-eastern-asian-population) documents Aldan/Amur and northeast Chinese stopovers. [International Crane Foundation](https://savingcranes.org/species/siberian-crane/) describes the Poyang wintering grounds. |
| Hooded Crane | [International Crane Foundation](https://savingcranes.org/species/hooded-crane/) describes breeding in Russia/northern China and wintering mainly at Izumi, with smaller groups in Korea and the middle Yangtze basin. |
| White-naped Crane | [Breeding and migration performance study](https://pmc.ncbi.nlm.nih.gov/articles/PMC9617902/) distinguishes the Mongolia–Poyang western population from the Amur–Korea/Japan eastern population. |
| Swan Goose | [USGS GPS study](https://www.usgs.gov/publications/migration-strategies-swan-geese-anser-cygnoides-northeast-mongolia): northeast Mongolia–Yalu estuary–Yangtze wetlands, including prolonged autumn staging. |
| Baikal Teal | [Nam et al., satellite study](https://www.jstage.jst.go.jp/article/osj/24/1/24_157/_article/-char/ja) identifies multiple spring routes from Korea to the Kolyma/lower Lena regions. [Japan's biodiversity portal](https://www.esabii.biodic.go.jp/database/migrantbirds/03.html) describes the wider winter range. |
| Great Knot | [BirdLife Australia](https://birdlife.org.au/bird-profiles/great-knot/) describes Siberian breeding, Australian wintering and Yellow Sea staging. [BirdLife International](https://www.birdlife.org/news/2026/08/19/great-knots-journey-along-the-east-asian-australasian-flyway/) describes Southeast Asian and northern Indian Ocean wintering areas. |
| Red-necked Stint | [Victorian Wader Study Group](https://vwsg.org.au/waders/geolocator-studies/red-necked-stint/): Siberia–Australia geolocator research, via diverse Asian and Indonesian stopovers. |
| Far Eastern Curlew | [Australian Government](https://www.dcceew.gov.au/environment/biodiversity/threatened/action-plan/eastern-curlew) describes Russia/China breeding and Australian migration timing. [BirdLife Australia](https://birdlife.org.au/bird-profiles/far-eastern-curlew/) describes coastal distribution and passage through East Asia. |

## Limits

- Seasonal sightings do not establish individual routes or migratory connectivity. Interpolated movement between half-month distributions is illustrative; it is not GPS tracking.
- Reporting coverage varies sharply between countries and seasons. Correction using all-bird reporting reduces this bias without removing it. Sparse Siberian records and missing periods can affect the apparent range and timing.
- Species-level records can combine populations with different migration routes. This matters especially for White-naped Crane. Individual tracking studies usually cover a small sample from one breeding or wintering area.
- Arctic Warbler is treated as *Phylloscopus borealis*, separately from Japanese and Kamchatka leaf warblers. Siberian Crane summaries refer to its eastern population.
- Geographic filtering defines this regional view. It is not a complete map of every population or every wintering site. Broad destination labels describe regular regional movements; occasional records are not evidence of a major migration route.
- Dots are visual samples, not counted birds or population estimates. Do not infer relative abundance from their number or density.

Map imagery: NASA. Coastlines, borders and lakes: Natural Earth. Regional context: [BirdLife International, East Asian–Australasian Flyway](https://www.birdlife.org/east-asian-australasian-flyway/).
