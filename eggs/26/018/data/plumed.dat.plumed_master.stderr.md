**Project ID:** [plumID:26.018]({{ '/' | absolute_url }}eggs/26/018/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
dseams_plumed.QiapmD.cpp:113:9: warning: ‘#pragma once’ in main file [-Wpragma-once-outside-header]
113 | #pragma once
|         ^~~~
dseams_plumed.QiapmD.cpp:145:9: warning: ‘#pragma once’ in main file [-Wpragma-once-outside-header]
145 | #pragma once
|         ^~~~
dseams_plumed.QiapmD.cpp:4163:9: warning: ‘#pragma once’ in main file [-Wpragma-once-outside-header]
4163 | #pragma once
|         ^~~~
dseams_plumed.QiapmD.cpp:12247:9: warning: ‘#pragma once’ in main file [-Wpragma-once-outside-header]
12247 | #pragma once
|         ^~~~
dseams_plumed.QiapmD.cpp: In function ‘void classifyBondsLeftFp64(molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<std::vector<int> >&, const chill::BondClassifier&, bool, const std::vector<int>*, const std::vector<int>*, bool)’:
dseams_plumed.QiapmD.cpp:5719:14: warning: unused variable ‘wide’ [-Wunused-variable]
5719 |   const bool wide =
|              ^~~~
dseams_plumed.QiapmD.cpp: In function ‘void chill::classifyBonds(molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<std::vector<int> >&, const BondClassifier&, bool, bool)’:
dseams_plumed.QiapmD.cpp:5966:29: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
5966 |   for (int iatom = 0; iatom < nList.size(); iatom++) {
|                       ~~~~~~^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘void chill::getIceType(molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<std::vector<int> >&, std::string, int, bool, std::string)’:
dseams_plumed.QiapmD.cpp:6259:17: warning: ignoring return value of ‘int sout::makePath(const std::string&)’, declared with attribute ‘nodiscard’ [-Wunused-result]
6259 |   sout::makePath(path);
|   ~~~~~~~~~~~~~~^~~~~~
dseams_plumed.QiapmD.cpp:3019:26: note: declared here
3019 | [[nodiscard]] inline int makePath(const std::string &path) {
|                          ^~~~~~~~
dseams_plumed.QiapmD.cpp:6261:17: warning: ignoring return value of ‘int sout::makePath(const std::string&)’, declared with attribute ‘nodiscard’ [-Wunused-result]
6261 |   sout::makePath(outputDirName);
|   ~~~~~~~~~~~~~~^~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:3019:26: note: declared here
3019 | [[nodiscard]] inline int makePath(const std::string &path) {
|                          ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘bool chill::q4q6ChillPlus(molSys::PointCloud<molSys::Point<double>, double>&, double, int, std::vector<double>&, std::vector<double>&, std::vector<double>&, std::vector<double>&)’:
dseams_plumed.QiapmD.cpp:6697:14: warning: unused variable ‘parallel’ [-Wunused-variable]
6697 |   const bool parallel = false;
|              ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘void chill::getIceTypePlus(molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<std::vector<int> >&, std::string, int, bool, std::string, bool)’:
dseams_plumed.QiapmD.cpp:8191:17: warning: ignoring return value of ‘int sout::makePath(const std::string&)’, declared with attribute ‘nodiscard’ [-Wunused-result]
8191 |   sout::makePath(path);
|   ~~~~~~~~~~~~~~^~~~~~
dseams_plumed.QiapmD.cpp:3019:26: note: declared here
3019 | [[nodiscard]] inline int makePath(const std::string &path) {
|                          ^~~~~~~~
dseams_plumed.QiapmD.cpp:8193:17: warning: ignoring return value of ‘int sout::makePath(const std::string&)’, declared with attribute ‘nodiscard’ [-Wunused-result]
8193 |   sout::makePath(outputDirName);
|   ~~~~~~~~~~~~~~^~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:3019:26: note: declared here
3019 | [[nodiscard]] inline int makePath(const std::string &path) {
|                          ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘int chill::printIceType(molSys::PointCloud<molSys::Point<double>, double>&, std::string, int, bool, std::string)’:
dseams_plumed.QiapmD.cpp:8410:17: warning: ignoring return value of ‘int sout::makePath(const std::string&)’, declared with attribute ‘nodiscard’ [-Wunused-result]
8410 |   sout::makePath(path);
|   ~~~~~~~~~~~~~~^~~~~~
dseams_plumed.QiapmD.cpp:3019:26: note: declared here
3019 | [[nodiscard]] inline int makePath(const std::string &path) {
|                          ^~~~~~~~
dseams_plumed.QiapmD.cpp:8412:17: warning: ignoring return value of ‘int sout::makePath(const std::string&)’, declared with attribute ‘nodiscard’ [-Wunused-result]
8412 |   sout::makePath(outputDirName);
|   ~~~~~~~~~~~~~~^~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:3019:26: note: declared here
3019 | [[nodiscard]] inline int makePath(const std::string &path) {
|                          ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘int chill::numStaggered(molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<std::vector<int> >&, int)’:
dseams_plumed.QiapmD.cpp:8496:7: warning: unused variable ‘num_bonds’ [-Wunused-variable]
8496 |   int num_bonds;              // No. of bonds of the jatom
|       ^~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘ring::CageAffiliation {anonymous}::batchSweep(const FrameContext&)’:
dseams_plumed.QiapmD.cpp:10577:14: warning: unused variable ‘threaded’ [-Wunused-variable]
10577 |   const bool threaded = false;
|              ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘bool nneigh::orthoFullCsr(const molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<int>*, double, std::vector<int>&, std::vector<int>&, bool, std::vector<std::vector<int> >*, const int*, bool*, bool)’:
dseams_plumed.QiapmD.cpp:19492:14: warning: unused variable ‘team’ [-Wunused-variable]
19492 |   const bool team = !nested && nSubset >= 256;
|              ^~~~
dseams_plumed.QiapmD.cpp: In function ‘std::vector<std::vector<int> > searchPacked({anonymous}::PackedRows, int, const std::vector<char>&, bool, SizeCounts, int, std::vector<int>*, int, int*, int)’:
dseams_plumed.QiapmD.cpp:23037:14: warning: unused variable ‘serial’ [-Wunused-variable]
23037 |   const bool serial = use <= 1;
|              ^~~~~~
dseams_plumed.QiapmD.cpp:23216:13: warning: unused variable ‘nFrom’ [-Wunused-variable]
23216 |   const int nFrom = static_cast<int>(from.size());
|             ^~~~~
dseams_plumed.QiapmD.cpp:23218:8: warning: unused variable ‘sparseCensus’ [-Wunused-variable]
23218 |   bool sparseCensus = false;
|        ^~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘primitive::Graph primitive::countAllRingsFromIndex(const std::vector<std::vector<int> >&, int)’:
dseams_plumed.QiapmD.cpp:23488:29: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
23488 |   for (int iatom = 0; iatom < neighHbondList.size(); iatom++) {
|                       ~~~~~~^~~~~~~~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:23492:25: warning: ignoring return value of ‘int primitive::findRings(Graph&, int, std::vector<int>&, int, int, int)’, declared with attribute ‘nodiscard’ [-Wunused-result]
23492 |     primitive::findRings(fullGraph, iatom, visited, maxDepth, depth);
|     ~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:20196:19: note: declared here
20196 | [[nodiscard]] int findRings(Graph &fullGraph, int v, std::vector<int> &visited, int maxDepth,
|                   ^~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘int primitive::findRings(Graph&, int, std::vector<int>&, int, int, int)’:
dseams_plumed.QiapmD.cpp:23569:27: warning: ignoring return value of ‘int primitive::findRings(Graph&, int, std::vector<int>&, int, int, int)’, declared with attribute ‘nodiscard’ [-Wunused-result]
23569 |       primitive::findRings(fullGraph, n, visited, maxDepth, depth, root);
|       ~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:23525:5: note: declared here
23525 | int primitive::findRings(Graph &fullGraph, int v, std::vector<int> &visited,
|     ^~~~~~~~~
dseams_plumed.QiapmD.cpp:23577:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<int>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
23577 |     for (int j = 0; j < fullGraph.pts[static_cast<std::size_t>(v)].neighListIndex.size(); j++) {
|                     ~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘primitive::Graph primitive::populateGraphFromIndices(const std::vector<std::vector<int> >&)’:
dseams_plumed.QiapmD.cpp:23667:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
23667 |   for (int i = 0; i < nList.size(); i++) {
|                   ~~^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:23663:7: warning: unused variable ‘nnumNeighbours’ [-Wunused-variable]
23663 |   int nnumNeighbours;         // Number of nearest neighbours for iatom
|       ^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:23664:14: warning: unused variable ‘jatom’ [-Wunused-variable]
23664 |   int iatom, jatom;           // Atom index being saved
|              ^~~~~
dseams_plumed.QiapmD.cpp: In function ‘void primitive::restoreEdgesFromIndices(Graph&, const std::vector<std::vector<int> >&)’:
dseams_plumed.QiapmD.cpp:23699:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
23699 |   for (int i = 0; i < nList.size(); i++) {
|                   ~~^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘void primitive::removeNonSPrings(Graph&)’:
dseams_plumed.QiapmD.cpp:23818:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<bool>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
23818 |   for (int i = 0; i < ringsToRemove.size(); i++) {
|                   ~~^~~~~~~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘int primitive::shortestPath(Graph&, int, int, std::vector<int>&, std::vector<int>&, int, int)’:
dseams_plumed.QiapmD.cpp:23876:34: warning: ignoring return value of ‘int primitive::shortestPath(Graph&, int, int, std::vector<int>&, std::vector<int>&, int, int)’, declared with attribute ‘nodiscard’ [-Wunused-result]
23876 |           primitive::shortestPath(fullGraph, n, goal, path, visited, maxDepth,
|           ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
23877 |                                   depth);   // Recursive call
|                                   ~~~~~~
dseams_plumed.QiapmD.cpp:23847:5: note: declared here
23847 | int primitive::shortestPath(Graph &fullGraph, int v, int goal,
|     ^~~~~~~~~
dseams_plumed.QiapmD.cpp: In member function ‘const std::vector<std::vector<int> >& primitive::RingUpdater::update(const std::vector<std::vector<int> >&)’:
dseams_plumed.QiapmD.cpp:24499:7: warning: unused variable ‘nThreads’ [-Wunused-variable]
24499 |   int nThreads = 1;
|       ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘bool nneigh::blockWindowRows(const molSys::PointCloud<molSys::Point<double>, double>&, double, const std::vector<char>*, std::vector<std::vector<int> >&, bool, bool)’:
dseams_plumed.QiapmD.cpp:25904:14: warning: variable ‘windowT0’ set but not used [-Wunused-but-set-variable]
25904 |   const auto windowT0 = std::chrono::steady_clock::now();
|              ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘std::vector<int> {anonymous}::nominatePacked(const molSys::PointCloud<molSys::Point<double>, double>&, int, int, double, const std::vector<int>*)’:
dseams_plumed.QiapmD.cpp:27552:14: warning: unused variable ‘parallelSearch’ [-Wunused-variable]
27552 |   const bool parallelSearch = false;
|              ^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘void {anonymous}::fillBothGraphsFromNom(const molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<int>&, int, std::vector<std::vector<int> >&, std::vector<std::vector<int> >&)’:
dseams_plumed.QiapmD.cpp:27942:13: warning: unused variable ‘n’ [-Wunused-variable]
27942 |   const int n = yCloud.nop;
|             ^
dseams_plumed.QiapmD.cpp: In function ‘void nneigh::kNearestCsr(const molSys::PointCloud<molSys::Point<double>, double>&, int, double, int, bool, std::vector<int>&, std::vector<int>&, bool)’:
dseams_plumed.QiapmD.cpp:28267:14: warning: unused variable ‘job’ [-Wunused-variable]
28267 |     CsrSlabs job{&nom, &deg, &cols, &offsets, n, k, 0};
|              ^~~
dseams_plumed.QiapmD.cpp: In function ‘std::vector<double> topoparam::calcCoverageArea(const molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<std::vector<int> >&, double)’:
dseams_plumed.QiapmD.cpp:28940:29: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
28940 |   for (int iring = 0; iring < rings.size(); iring++) {
|                       ~~~~~~^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘bool seams::product::{anonymous}::int8ProductChecks(int, int, int, const signed char*, int, const signed char*, int, const int*)’:
dseams_plumed.QiapmD.cpp:30137:15: warning: ISO C++ does not support ‘__int128’ for ‘type name’ [-Wpedantic]
30137 |   std::vector<__int128> bRow(static_cast<std::size_t>(k), 0);
|               ^~~~~~~~
dseams_plumed.QiapmD.cpp:30138:15: warning: ISO C++ does not support ‘__int128’ for ‘type name’ [-Wpedantic]
30138 |   std::vector<__int128> bRowW(static_cast<std::size_t>(k), 0);
|               ^~~~~~~~
dseams_plumed.QiapmD.cpp:30139:15: warning: ISO C++ does not support ‘__int128’ for ‘type name’ [-Wpedantic]
30139 |   std::vector<__int128> aCol(static_cast<std::size_t>(k), 0);
|               ^~~~~~~~
dseams_plumed.QiapmD.cpp:30142:13: warning: ISO C++ does not support ‘__int128’ for ‘b’ [-Wpedantic]
30142 |       const __int128 b = B[t * ldb + j];
|             ^~~~~~~~
dseams_plumed.QiapmD.cpp:30151:5: warning: ISO C++ does not support ‘__int128’ for ‘want’ [-Wpedantic]
30151 |     __int128 want = 0;
|     ^~~~~~~~
dseams_plumed.QiapmD.cpp:30152:5: warning: ISO C++ does not support ‘__int128’ for ‘wantW’ [-Wpedantic]
30152 |     __int128 wantW = 0;
|     ^~~~~~~~
dseams_plumed.QiapmD.cpp:30154:13: warning: ISO C++ does not support ‘__int128’ for ‘a’ [-Wpedantic]
30154 |       const __int128 a = A[i * lda + t];
|             ^~~~~~~~
dseams_plumed.QiapmD.cpp:30158:5: warning: ISO C++ does not support ‘__int128’ for ‘got’ [-Wpedantic]
30158 |     __int128 got = 0;
|     ^~~~~~~~
dseams_plumed.QiapmD.cpp:30159:5: warning: ISO C++ does not support ‘__int128’ for ‘gotW’ [-Wpedantic]
30159 |     __int128 gotW = 0;
|     ^~~~~~~~
dseams_plumed.QiapmD.cpp:30161:13: warning: ISO C++ does not support ‘__int128’ for ‘p’ [-Wpedantic]
30161 |       const __int128 p = P[static_cast<std::size_t>(i) * static_cast<std::size_t>(n) + static_cast<std::size_t>(j)];
|             ^~~~~~~~
dseams_plumed.QiapmD.cpp:30170:5: warning: ISO C++ does not support ‘__int128’ for ‘want’ [-Wpedantic]
30170 |     __int128 want = 0;
|     ^~~~~~~~
dseams_plumed.QiapmD.cpp:30174:5: warning: ISO C++ does not support ‘__int128’ for ‘got’ [-Wpedantic]
30174 |     __int128 got = 0;
|     ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘int ring::assignPolygonType(const std::vector<std::vector<int> >&, std::vector<int>&, const std::vector<int>&)’:
dseams_plumed.QiapmD.cpp:30802:29: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
30802 |   for (int iring = 0; iring < rings.size(); iring++) {
|                       ~~~~~~^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘std::vector<int> ring::findsCommonElements(const std::vector<int>&, const std::vector<int>&)’:
dseams_plumed.QiapmD.cpp:30837:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<int>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
30837 |   for (int i = 0; i < ring1.size(); i++) {
|                   ~~^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘void {anonymous}::ddcChains(const std::vector<std::vector<int> >&, const std::vector<int>&, const std::array<IntBuf, 6>&, int, int, std::vector<DdcChain>&)’:
dseams_plumed.QiapmD.cpp:32774:22: warning: comparison of integer expressions of different signedness: ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} and ‘int’ [-Wsign-compare]
32774 |   if (bcFromC.size() < C.size()) {
|       ~~~~~~~~~~~~~~~^~~~~~~~~~
dseams_plumed.QiapmD.cpp: In lambda function:
dseams_plumed.QiapmD.cpp:34842:26: warning: ignoring return value of ‘int ring::findPrismatic(const std::vector<std::vector<int> >&, std::vector<int>&, std::vector<strucType>&, int, int, std::vector<int>&, const RingSearchIndex&)’, declared with attribute ‘nodiscard’ [-Wunused-result]
34842 |       ring::findPrismatic(rings, listHC, ringType, iring, jring, prismaticRings,
|       ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
34843 |                           index);
|                           ~~~~~~
dseams_plumed.QiapmD.cpp:9961:19: note: declared here
9961 | [[nodiscard]] int findPrismatic(const std::vector<std::vector<int>> &rings,
|                   ^~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:34846:26: warning: ignoring return value of ‘int ring::findPrismatic(const std::vector<std::vector<int> >&, std::vector<int>&, std::vector<strucType>&, int, int, std::vector<int>&, const RingSearchIndex&)’, declared with attribute ‘nodiscard’ [-Wunused-result]
34846 |       ring::findPrismatic(rings, listHC, ringType, jring, iring, prismaticRings,
|       ~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
34847 |                           index);
|                           ~~~~~~
dseams_plumed.QiapmD.cpp:9961:19: note: declared here
9961 | [[nodiscard]] int findPrismatic(const std::vector<std::vector<int>> &rings,
|                   ^~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘bool ring::basalNeighbours(const std::vector<std::vector<int> >&, std::vector<int>&, int, int)’:
dseams_plumed.QiapmD.cpp:35111:8: warning: variable ‘neighTwo’ set but not used [-Wunused-but-set-variable]
35111 |        neighTwo = false; // Neighbour for atomOne, or neighbour for atomTwo
|        ^~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘bool ring::notNeighboursOfRing(const std::vector<std::vector<int> >&, std::vector<int>&, const std::vector<int>&)’:
dseams_plumed.QiapmD.cpp:35184:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<int>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
35184 |   for (int i = 0; i < triplet.size(); i++) {
|                   ~~^~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:35188:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<int>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
35188 |     for (int j = 0; j < ring.size(); j++) {
|                     ~~^~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘std::vector<int> ring::findMixedRings(const std::vector<std::vector<int> >&, std::vector<strucType>&, std::vector<int>&, std::vector<int>&)’:
dseams_plumed.QiapmD.cpp:35325:29: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<ring::strucType>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
35325 |   for (int iring = 0; iring < ringType.size(); iring++) {
|                       ~~~~~~^~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘int ring::getAtomTypesTopoBulk(const std::vector<std::vector<int> >&, const std::vector<strucType>&, std::vector<cage::iceType>&)’:
dseams_plumed.QiapmD.cpp:35371:29: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<ring::strucType>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
35371 |   for (int iring = 0; iring < ringType.size(); iring++) {
|                       ~~~~~~^~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘int ring::getStrucNumbers(const std::vector<strucType>&, const std::vector<cage::Cage>&, int&, int&, int&, int&, int&)’:
dseams_plumed.QiapmD.cpp:35460:29: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<cage::Cage>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
35460 |   for (int icage = 0; icage < cageList.size(); icage++) {
|                       ~~~~~~^~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:35475:29: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<ring::strucType>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
35475 |   for (int iring = 0; iring < ringType.size(); iring++) {
|                       ~~~~~~^~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp: In function ‘bool prism3::basalRingsSeparation(molSys::PointCloud<molSys::Point<double>, double>&, const std::vector<int>&, const std::vector<int>&, double)’:
dseams_plumed.QiapmD.cpp:35679:7: warning: variable ‘index’ set but not used [-Wunused-but-set-variable]
35679 |   int index = -1; // starting index
|       ^~~~~
dseams_plumed.QiapmD.cpp: At global scope:
dseams_plumed.QiapmD.cpp:37039:78: warning: optimization attribute on ‘topo::LocalKey topo::localKeyFromGraph(LocalGraph&, int, uint64_t*)’ follows definition but the attribute doesn’t match [-Wattributes]
37039 | LocalKey localKeyFromGraph(LocalGraph &g, int hops, std::uint64_t *refinement);
|                                                                              ^
dseams_plumed.QiapmD.cpp:36539:10: note: previous definition of ‘topo::LocalKey topo::localKeyFromGraph(LocalGraph&, int, uint64_t*)’ here
36539 | LocalKey localKeyFromGraph(LocalGraph &g, int hops, std::uint64_t *refinement) {
|          ^~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:37041:51: warning: optimization attribute on ‘void topo::fillLocalGraph(LocalGraph&, const Rows&, int, int, const std::vector<int>&)’ follows definition but the attribute doesn’t match [-Wattributes]
37041 |                     const std::vector<int> &colors);
|                                                   ^
dseams_plumed.QiapmD.cpp:36476:6: note: previous definition of ‘void topo::fillLocalGraph(LocalGraph&, const Rows&, int, int, const std::vector<int>&)’ here
36476 | void fillLocalGraph(LocalGraph &g, const Rows &rows, int atom, int hops,
|      ^~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:37451:7: warning: ‘PLMD::colvar::DseamsCages’ declared with greater visibility than the type of its field ‘PLMD::colvar::DseamsCages::library_’ [-Wattributes]
37451 | class DseamsCages : public Colvar {
|       ^~~~~~~~~~~
dseams_plumed.QiapmD.cpp:37451:7: warning: ‘PLMD::colvar::DseamsCages’ declared with greater visibility than the type of its field ‘PLMD::colvar::DseamsCages::libraries_’ [-Wattributes]
dseams_plumed.QiapmD.cpp: In instantiation of ‘void {anonymous}::BoundedBalls::fillList(const Graph&, int, const std::vector<int>&) [with Graph = {anonymous}::PackedRows]’:
dseams_plumed.QiapmD.cpp:23180:19:   required from here
23180 |     balls.fillList(adjacency, 2, reach);
|     ~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:20493:16: warning: unused variable ‘parallel’ [-Wunused-variable]
20493 |     const bool parallel = false;
|                ^~~~~~~~
dseams_plumed.QiapmD.cpp: In instantiation of ‘void {anonymous}::ringsThroughRows(const Row&, const Row&, const Row&, int, int, Out&) [with Row = RingRow; Out = IntBuf]’:
dseams_plumed.QiapmD.cpp:34144:21:   required from here
34144 |     ringsThroughRows(rowOf[k], rowOf[(k + 1) % 6], rowOf[(k + 2) % 6], iring, -1,
|     ~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
34145 |                      T[static_cast<std::size_t>(k)]);
|                      ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:32407:12: warning: comparison of integer expressions of different signedness: ‘size_t’ {aka ‘long unsigned int’} and ‘int’ [-Wsign-compare]
32407 |   while (i < A.size() && j < B.size() && k < C.size()) {
|          ~~^~~~~~~~~~
dseams_plumed.QiapmD.cpp:32407:28: warning: comparison of integer expressions of different signedness: ‘size_t’ {aka ‘long unsigned int’} and ‘int’ [-Wsign-compare]
32407 |   while (i < A.size() && j < B.size() && k < C.size()) {
|                          ~~^~~~~~~~~~
dseams_plumed.QiapmD.cpp:32407:44: warning: comparison of integer expressions of different signedness: ‘size_t’ {aka ‘long unsigned int’} and ‘int’ [-Wsign-compare]
32407 |   while (i < A.size() && j < B.size() && k < C.size()) {
|                                          ~~^~~~~~~~~~
dseams_plumed.QiapmD.cpp: In instantiation of ‘void {anonymous}::ringsThroughRows(const Row&, const Row&, const Row&, int, int, Out&) [with Row = RingRow; Out = std::vector<int>]’:
dseams_plumed.QiapmD.cpp:32436:19:   required from ‘void {anonymous}::ringsThrough(const ring::RingSearchIndex&, int, int, int, int, int, Out&) [with Out = std::vector<int>]’
32436 |   ringsThroughRows(atomRow(index, a), atomRow(index, b), atomRow(index, c),
|   ~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
32437 |                    skipA, skipB, out);
|                    ~~~~~~~~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:35258:17:   required from here
35258 |     ringsThrough(index, iTriplet[0], iTriplet[1], iTriplet[2], iring, jring,
|     ~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
35259 |                  candidates);
|                  ~~~~~~~~~~~
dseams_plumed.QiapmD.cpp:32407:12: warning: comparison of integer expressions of different signedness: ‘size_t’ {aka ‘long unsigned int’} and ‘int’ [-Wsign-compare]
32407 |   while (i < A.size() && j < B.size() && k < C.size()) {
|          ~~^~~~~~~~~~
dseams_plumed.QiapmD.cpp:32407:28: warning: comparison of integer expressions of different signedness: ‘size_t’ {aka ‘long unsigned int’} and ‘int’ [-Wsign-compare]
32407 |   while (i < A.size() && j < B.size() && k < C.size()) {
|                          ~~^~~~~~~~~~
dseams_plumed.QiapmD.cpp:32407:44: warning: comparison of integer expressions of different signedness: ‘size_t’ {aka ‘long unsigned int’} and ‘int’ [-Wsign-compare]
32407 |   while (i < A.size() && j < B.size() && k < C.size()) {
|                                          ~~^~~~~~~~~~
</pre>
{% endraw %}
