# DATA401 Map Project

## Data used (WIP)
- [Philippine Municipality Boundary](https://data.humdata.org/dataset/cod-ab-phl) (phl_admbnda_adm3_psa_namria_20231106)
- [Metro Manila 100 year Flood](https://drive.google.com/drive/folders/1ALE4-E9c-4AGjm1fqiPprWHrLUskeY9o)
- [Overpass turbo API](https://overpass-turbo.eu/) (schools, universities, hospitals)

## Setup
1. Clone the repository
```
git clone https://github.com/dyitsme/DATA401_map.git
```
2. Download the data as shown in the previous section
3. You can now view and edit the project
4. If you have made any changes, push it first in a separate branch (only applicable to invited contributors)
```
git add .
git commit -m "<YOUR COMMENT FOR CHANGES>"
git checkout -b <branch_name>
git push origin <branch_name>
```

Note: The QGIS project file and the data should all be in the same folder. It is better to put the data in their respective folders to avoid clutter. If QGIS still complains that it can't find the data, try to either make it auto-find or manually find the data.