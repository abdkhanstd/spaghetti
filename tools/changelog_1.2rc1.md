# Changes

Version 1.2rc1 (2019-02-27)

We closed a total of 160 issues (enhancements and bug fixes) through 60 pull requests, since our last release on 2018-11-01.

## Issues Closed
  - Coverage testing (#239)
  - update .travis.yml and introduce .coveragerc similar to pysal/giddy#81 (#238)
  - Update `bug` template (#237)
  - Update issue templates (#236)
  - Add .github directory based on libpysal (#234)
  - Adding community info (#235)
  - remove README.rst (#223)
  - Removing README.rst and updating setup.py (#233)
  - pysal/giddy#77 (reference labels) (#231)
  - Ref docs (#232)
  - Api site doc (#230)
  - correction in notebooks/Network_Usage.ipynb (#229)
  - edges_to_arcs naming convention (#227)
  - altering edges_to_arcs crosswalk name (#228)
  - Improve in-line docs -- 24PullRequests for Christmas (#202)
  - updating utils.py docs (#226)
  - updating all analysis.py docs (#224)
  - Docs split arcs (#222)
  - Docs allneighbordistances (#221)
  - updating docs for full_distance_matrix (#220)
  - notes for simulate_observations (#219)
  - Docs net funcs (#218)
  - bug in snapping points? (#125)
  - Deprecation: Container-Based Linux Build Environments (#188)
  - Remove sorted edges (#216)
  - purpose of class SortedEdges(OrderedDict)? (#90)
  - geometry notes in _newpoint_coords (#215)
  - count_per_link -- updating docs (#214)
  - TravisCI error raise ReadTimeoutError(self._pool, None, 'Read timed out.') (#213)
  - variable declaration correction in _snap_to_link (#212)
  - compute_distance_to_vertices -- in-line doc improvement (#211)
  - improved in-line comments in network.Network.distancebandweights (#210)
  - improved in-line comments in network.Network.contiguityweights (#209)
  - improved in-line comments in network.Network._docs_evaluate_napts (#208)
  - improved in-line comments in network.Network._yield_napts (#207)
  - improved in-line comments in network.Network.extractgraph (#206)
  - improved in-line comments in network.Network.extract_components (#205)
  - improved in-line comments in network.Network._round_sig (#204)
  - improved in-line comments in network.Network.__init__ (#203)
  - improved in-line comments in _extractnetwork (#201)
  - minor spaghetti/util.py doc clean (#200)
  - update notebooks following #185 (#187)
  - README graphic legend update (#197)
  - Update notebooks (#199)
  - correcting arc -- arcs attribute (#193)
  - attribute declaration error (network.Network.arc) (#192)
  - (from pysal.network) Edge ID data structure #933 (#176)
  - (from pysal.network) network ring bug #655 (#184)
  - Debug of data structure/algo that led to ring/graph errors (#185)
  - Creating Network instance from road shapefile fails; ValueError: list.remove(x): x not in list (#9)
  - (from pysal.network) Revisit graph weights in network module #496 (#186)
  - Updating spaghetti ReadTheDocs (#183)
  - tree not recorded in same network arc (#180)
  - Nearest tree update (#182)
  - clean/create more coherent and uniform variable names (#49)
  - Updating/standardizing network/graph element naming (#181)
  - Dijkstra maintenance (#179)
  - [MAINT] dijkstra (#178)
  - Adding .png of snapped point to README.md (#177)
  - fixing bug in distancebandweights (#175)
  - bug in network.Network.distancebandweights (#174)
  - determine necessity of test_distance_band_weights (#62)
  - updating ReadTheDocs following #172  (#173)
  - Pep8 docs review (#172)
  - record connected components (#168)
  - [WIP] contiguityweights and connected_components (#171)
  - add break condition in contiguityweights() (#170)
  - Edge Weighting pysal/pysal #609 (#66)
  - Merge unittest scripts (#169)
  - Further streamline unittests (#157)
  - api docs (#162)
  - network element as geodataframe (#143)
  - Refactor element as gdf (#167)
  - Restructure docs (#166)
  - Non responsive docs (#165)
  - typo in dijkstra reference (#163)
  - Update api docs (#164)
  - Update api (#161)
  - cleaning up notebooks/Snapping_Demonstration.ipynb (#160)
  - Update notebooks (#159)
  - add minor test for _round_sig (#152)
  - Round sig test (#156)
  - updating element_as_gdf.rst (#155)
  - Update doc element to gdf (#154)
  - Streamline unittests (#147)
  - Streamline unittests (#153)
  - ENH: element_to_gdf() (#145)
  - correcting list comp syntax in _round_sig (#151)
  - error in _round_sig() when a coordinate is 0.0 (#150)
  - [ENH] streets/network and points need to be in the same CRS/EPSG (#71)
  - update markdown docs fromSpaghetti_Pointpatterns_Empirical.ipynb (#146)
  - updating typo in notebooks/Spaghetti_Pointpatterns_Empirical.ipynb (#149)
  - Minor notebook update (#148)
  - update spaghetti info on pysal.site (#144)
  - fix RuntimeWarning in analysis.py (#140)
  - usage of networkx (#141)
  - updating notebooks (#142)
  - update spaghetti landing site notebook links (#139)
  - rerunning notebooks (#138)
  - travis build still failing (#127)

## Pull Requests
  - Coverage testing (#239)
  - Update `bug` template (#237)
  - Update issue templates (#236)
  - Adding community info (#235)
  - Removing README.rst and updating setup.py (#233)
  - Ref docs (#232)
  - Api site doc (#230)
  - correction in notebooks/Network_Usage.ipynb (#229)
  - altering edges_to_arcs crosswalk name (#228)
  - updating utils.py docs (#226)
  - updating all analysis.py docs (#224)
  - Docs split arcs (#222)
  - Docs allneighbordistances (#221)
  - updating docs for full_distance_matrix (#220)
  - notes for simulate_observations (#219)
  - Docs net funcs (#218)
  - Remove sorted edges (#216)
  - geometry notes in _newpoint_coords (#215)
  - count_per_link -- updating docs (#214)
  - variable declaration correction in _snap_to_link (#212)
  - compute_distance_to_vertices -- in-line doc improvement (#211)
  - improved in-line comments in network.Network.distancebandweights (#210)
  - improved in-line comments in network.Network.contiguityweights (#209)
  - improved in-line comments in network.Network._docs_evaluate_napts (#208)
  - improved in-line comments in network.Network._yield_napts (#207)
  - improved in-line comments in network.Network.extractgraph (#206)
  - improved in-line comments in network.Network.extract_components (#205)
  - improved in-line comments in network.Network._round_sig (#204)
  - improved in-line comments in network.Network.__init__ (#203)
  - improved in-line comments in _extractnetwork (#201)
  - minor spaghetti/util.py doc clean (#200)
  - Update notebooks (#199)
  - correcting arc -- arcs attribute (#193)
  - Debug of data structure/algo that led to ring/graph errors (#185)
  - Updating spaghetti ReadTheDocs (#183)
  - Nearest tree update (#182)
  - Updating/standardizing network/graph element naming (#181)
  - Dijkstra maintenance (#179)
  - Adding .png of snapped point to README.md (#177)
  - fixing bug in distancebandweights (#175)
  - updating ReadTheDocs following #172  (#173)
  - Pep8 docs review (#172)
  - [WIP] contiguityweights and connected_components (#171)
  - Merge unittest scripts (#169)
  - Refactor element as gdf (#167)
  - Restructure docs (#166)
  - Non responsive docs (#165)
  - Update api docs (#164)
  - Update api (#161)
  - cleaning up notebooks/Snapping_Demonstration.ipynb (#160)
  - Update notebooks (#159)
  - Round sig test (#156)
  - updating element_as_gdf.rst (#155)
  - Update doc element to gdf (#154)
  - Streamline unittests (#153)
  - ENH: element_to_gdf() (#145)
  - correcting list comp syntax in _round_sig (#151)
  - updating typo in notebooks/Spaghetti_Pointpatterns_Empirical.ipynb (#149)
  - updating notebooks (#142)
  - rerunning notebooks (#138)

The following individuals contributed to this release:

  - James Gaboardi