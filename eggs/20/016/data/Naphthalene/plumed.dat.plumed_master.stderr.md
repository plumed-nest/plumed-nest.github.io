**Project ID:** [plumID:20.016]({{ '/' | absolute_url }}eggs/20/016/)  
Stderr for source:  Naphthalene/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
PairOrientationalEntropy.cpp: In constructor ‘PLMD::colvar::PairOrientationalEntropy::PairOrientationalEntropy(const PLMD::ActionOptions&)’:
PairOrientationalEntropy.cpp:193:27: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     for(unsigned int i=0;i<nhist_[0];i++) {
                           ^
PairOrientationalEntropy.cpp:194:30: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
        for(unsigned int j=0;j<nhist_[1];j++) {
                              ^
PairOrientationalEntropy.cpp:252:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=0;i<nhist_[0];++i){
                     ^
PairOrientationalEntropy.cpp:256:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=0;i<nhist_[1];++i){
                     ^
PairOrientationalEntropy.cpp: In member function ‘virtual void PLMD::colvar::PairOrientationalEntropy::calculate()’:
PairOrientationalEntropy.cpp:511:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned i=0;i<nhist_[0];++i){
                        ^
PairOrientationalEntropy.cpp:512:27: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
         for(unsigned j=0;j<nhist_[1];++j){
                           ^
PairOrientationalEntropy.cpp:523:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=0;i<nhist_[0];++i){
                     ^
PairOrientationalEntropy.cpp:524:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=0;j<nhist_[1];++j){
                        ^
PairOrientationalEntropy.cpp:562:25: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
       for(unsigned i=0;i<nhist_[0];++i){
                         ^
PairOrientationalEntropy.cpp:563:27: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
         for(unsigned j=0;j<nhist_[1];++j){
                           ^
PairOrientationalEntropy.cpp:581:23: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     for(unsigned i=0;i<nhist_[0];++i){
                       ^
PairOrientationalEntropy.cpp:582:26: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
        for(unsigned j=0;j<nhist_[1];++j){
                          ^
PairOrientationalEntropy.cpp:593:23: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     for(unsigned i=0;i<nhist_[0];++i){
                       ^
PairOrientationalEntropy.cpp:594:26: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
        for(unsigned j=0;j<nhist_[1];++j){
                          ^
PairOrientationalEntropy.cpp: In member function ‘double PLMD::colvar::PairOrientationalEntropy::integrate(PLMD::Matrix<double>, std::vector<double>) const’:
PairOrientationalEntropy.cpp:626:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropy.cpp:627:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=1;j<(nhist_[1]-1);++j){
                        ^
PairOrientationalEntropy.cpp:632:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropy.cpp:636:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned j=1;j<(nhist_[1]-1);++j){
                     ^
PairOrientationalEntropy.cpp: In member function ‘PLMD::Vector PLMD::colvar::PairOrientationalEntropy::integrate(PLMD::Matrix<PLMD::VectorGeneric<3u> >, std::vector<double>) const’:
PairOrientationalEntropy.cpp:653:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropy.cpp:654:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=1;j<(nhist_[1]-1);++j){
                        ^
PairOrientationalEntropy.cpp:659:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropy.cpp:663:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned j=1;j<(nhist_[1]-1);++j){
                     ^
PairOrientationalEntropy.cpp: In member function ‘PLMD::Tensor PLMD::colvar::PairOrientationalEntropy::integrate(PLMD::Matrix<PLMD::TensorGeneric<3u, 3u> >, std::vector<double>) const’:
PairOrientationalEntropy.cpp:680:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropy.cpp:681:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=1;j<(nhist_[1]-1);++j){
                        ^
PairOrientationalEntropy.cpp:686:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropy.cpp:690:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned j=1;j<(nhist_[1]-1);++j){
                     ^
PairOrientationalEntropy.cpp: In member function ‘void PLMD::colvar::PairOrientationalEntropy::outputGofr(PLMD::Matrix<double>, const char*)’:
PairOrientationalEntropy.cpp:705:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=0;i<nhist_[0];++i){
                     ^
PairOrientationalEntropy.cpp:706:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=0;j<nhist_[1];++j){
                        ^
PairOrientationalEntropyPerpendicular.cpp: In constructor ‘PLMD::colvar::PairOrientationalEntropyPerpendicular::PairOrientationalEntropyPerpendicular(const PLMD::ActionOptions&)’:
PairOrientationalEntropyPerpendicular.cpp:199:27: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     for(unsigned int i=0;i<nhist_[0];i++) {
                           ^
PairOrientationalEntropyPerpendicular.cpp:200:30: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
        for(unsigned int j=0;j<nhist_[1];j++) {
                              ^
PairOrientationalEntropyPerpendicular.cpp:259:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=0;i<nhist_[0];++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:263:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=0;i<nhist_[1];++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp: In member function ‘virtual void PLMD::colvar::PairOrientationalEntropyPerpendicular::calculate()’:
PairOrientationalEntropyPerpendicular.cpp:600:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned i=0;i<nhist_[0];++i){
                        ^
PairOrientationalEntropyPerpendicular.cpp:601:27: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
         for(unsigned j=0;j<nhist_[1];++j){
                           ^
PairOrientationalEntropyPerpendicular.cpp:612:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=0;i<nhist_[0];++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:613:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=0;j<nhist_[1];++j){
                        ^
PairOrientationalEntropyPerpendicular.cpp:655:25: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
       for(unsigned i=0;i<nhist_[0];++i){
                         ^
PairOrientationalEntropyPerpendicular.cpp:656:27: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
         for(unsigned j=0;j<nhist_[1];++j){
                           ^
PairOrientationalEntropyPerpendicular.cpp:678:23: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     for(unsigned i=0;i<nhist_[0];++i){
                       ^
PairOrientationalEntropyPerpendicular.cpp:679:26: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
        for(unsigned j=0;j<nhist_[1];++j){
                          ^
PairOrientationalEntropyPerpendicular.cpp:690:23: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     for(unsigned i=0;i<nhist_[0];++i){
                       ^
PairOrientationalEntropyPerpendicular.cpp:691:26: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
        for(unsigned j=0;j<nhist_[1];++j){
                          ^
PairOrientationalEntropyPerpendicular.cpp: In member function ‘double PLMD::colvar::PairOrientationalEntropyPerpendicular::integrate(PLMD::Matrix<double>, std::vector<double>) const’:
PairOrientationalEntropyPerpendicular.cpp:723:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:724:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=1;j<(nhist_[1]-1);++j){
                        ^
PairOrientationalEntropyPerpendicular.cpp:729:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:733:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned j=1;j<(nhist_[1]-1);++j){
                     ^
PairOrientationalEntropyPerpendicular.cpp: In member function ‘PLMD::Vector PLMD::colvar::PairOrientationalEntropyPerpendicular::integrate(PLMD::Matrix<PLMD::VectorGeneric<3u> >, std::vector<double>) const’:
PairOrientationalEntropyPerpendicular.cpp:750:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:751:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=1;j<(nhist_[1]-1);++j){
                        ^
PairOrientationalEntropyPerpendicular.cpp:756:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:760:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned j=1;j<(nhist_[1]-1);++j){
                     ^
PairOrientationalEntropyPerpendicular.cpp: In member function ‘PLMD::Tensor PLMD::colvar::PairOrientationalEntropyPerpendicular::integrate(PLMD::Matrix<PLMD::TensorGeneric<3u, 3u> >, std::vector<double>) const’:
PairOrientationalEntropyPerpendicular.cpp:777:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:778:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=1;j<(nhist_[1]-1);++j){
                        ^
PairOrientationalEntropyPerpendicular.cpp:783:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=1;i<(nhist_[0]-1);++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:787:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned j=1;j<(nhist_[1]-1);++j){
                     ^
PairOrientationalEntropyPerpendicular.cpp: In member function ‘void PLMD::colvar::PairOrientationalEntropyPerpendicular::outputGofr(PLMD::Matrix<double>, const char*)’:
PairOrientationalEntropyPerpendicular.cpp:802:21: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(unsigned i=0;i<nhist_[0];++i){
                     ^
PairOrientationalEntropyPerpendicular.cpp:803:24: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
      for(unsigned j=0;j<nhist_[1];++j){
                        ^
</pre>
{% endraw %}
