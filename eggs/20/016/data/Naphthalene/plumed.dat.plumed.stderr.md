**Project ID:** [plumID:20.016]({{ '/' | absolute_url }}eggs/20/016/)  
Stderr for source:  Naphthalene/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
PairOrientationalEntropy.s2PO5V.cpp: In constructor ‘PLMD::colvar::PairOrientationalEntropy::PairOrientationalEntropy(const PLMD::ActionOptions&)’:
PairOrientationalEntropy.s2PO5V.cpp:193:27: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
193 |     for(unsigned int i=0;i<nhist_[0];i++) {
PairOrientationalEntropy.s2PO5V.cpp:194:30: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
194 |        for(unsigned int j=0;j<nhist_[1];j++) {
PairOrientationalEntropy.s2PO5V.cpp:252:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
252 |   for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropy.s2PO5V.cpp:256:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
256 |   for(unsigned i=0;i<nhist_[1];++i){
PairOrientationalEntropy.s2PO5V.cpp: In member function ‘virtual void PLMD::colvar::PairOrientationalEntropy::calculate()’:
PairOrientationalEntropy.s2PO5V.cpp:511:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
511 |      for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropy.s2PO5V.cpp:512:27: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
512 |         for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropy.s2PO5V.cpp:523:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
523 |   for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropy.s2PO5V.cpp:524:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
524 |      for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropy.s2PO5V.cpp:562:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
562 |       for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropy.s2PO5V.cpp:563:27: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
563 |         for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropy.s2PO5V.cpp:581:23: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
581 |     for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropy.s2PO5V.cpp:582:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
582 |        for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropy.s2PO5V.cpp:593:23: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
593 |     for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropy.s2PO5V.cpp:594:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
594 |        for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropy.s2PO5V.cpp: In member function ‘double PLMD::colvar::PairOrientationalEntropy::integrate(PLMD::Matrix<double>, std::vector<double>) const’:
PairOrientationalEntropy.s2PO5V.cpp:626:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
626 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:627:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
627 |      for(unsigned j=1;j<(nhist_[1]-1);++j){
|                       ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:632:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
632 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:636:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
636 |   for(unsigned j=1;j<(nhist_[1]-1);++j){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp: In member function ‘PLMD::Vector PLMD::colvar::PairOrientationalEntropy::integrate(PLMD::Matrix<PLMD::VectorGeneric<3> >, std::vector<double>) const’:
PairOrientationalEntropy.s2PO5V.cpp:653:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
653 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:654:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
654 |      for(unsigned j=1;j<(nhist_[1]-1);++j){
|                       ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:659:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
659 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:663:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
663 |   for(unsigned j=1;j<(nhist_[1]-1);++j){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp: In member function ‘PLMD::Tensor PLMD::colvar::PairOrientationalEntropy::integrate(PLMD::Matrix<PLMD::TensorGeneric<3, 3> >, std::vector<double>) const’:
PairOrientationalEntropy.s2PO5V.cpp:680:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
680 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:681:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
681 |      for(unsigned j=1;j<(nhist_[1]-1);++j){
|                       ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:686:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
686 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp:690:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
690 |   for(unsigned j=1;j<(nhist_[1]-1);++j){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropy.s2PO5V.cpp: In member function ‘void PLMD::colvar::PairOrientationalEntropy::outputGofr(PLMD::Matrix<double>, const char*)’:
PairOrientationalEntropy.s2PO5V.cpp:705:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
705 |   for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropy.s2PO5V.cpp:706:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
706 |      for(unsigned j=0;j<nhist_[1];++j){
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
PairOrientationalEntropyPerpendicular.QtIdmk.cpp: In constructor ‘PLMD::colvar::PairOrientationalEntropyPerpendicular::PairOrientationalEntropyPerpendicular(const PLMD::ActionOptions&)’:
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:199:27: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
199 |     for(unsigned int i=0;i<nhist_[0];i++) {
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:200:30: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
200 |        for(unsigned int j=0;j<nhist_[1];j++) {
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:259:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
259 |   for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:263:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
263 |   for(unsigned i=0;i<nhist_[1];++i){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp: In member function ‘virtual void PLMD::colvar::PairOrientationalEntropyPerpendicular::calculate()’:
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:600:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
600 |      for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:601:27: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
601 |         for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:612:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
612 |   for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:613:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
613 |      for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:655:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
655 |       for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:656:27: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
656 |         for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:678:23: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
678 |     for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:679:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
679 |        for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:690:23: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
690 |     for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:691:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
691 |        for(unsigned j=0;j<nhist_[1];++j){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp: In member function ‘double PLMD::colvar::PairOrientationalEntropyPerpendicular::integrate(PLMD::Matrix<double>, std::vector<double>) const’:
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:723:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
723 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:724:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
724 |      for(unsigned j=1;j<(nhist_[1]-1);++j){
|                       ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:729:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
729 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:733:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
733 |   for(unsigned j=1;j<(nhist_[1]-1);++j){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp: In member function ‘PLMD::Vector PLMD::colvar::PairOrientationalEntropyPerpendicular::integrate(PLMD::Matrix<PLMD::VectorGeneric<3> >, std::vector<double>) const’:
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:750:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
750 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:751:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
751 |      for(unsigned j=1;j<(nhist_[1]-1);++j){
|                       ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:756:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
756 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:760:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
760 |   for(unsigned j=1;j<(nhist_[1]-1);++j){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp: In member function ‘PLMD::Tensor PLMD::colvar::PairOrientationalEntropyPerpendicular::integrate(PLMD::Matrix<PLMD::TensorGeneric<3, 3> >, std::vector<double>) const’:
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:777:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
777 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:778:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
778 |      for(unsigned j=1;j<(nhist_[1]-1);++j){
|                       ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:783:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
783 |   for(unsigned i=1;i<(nhist_[0]-1);++i){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:787:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
787 |   for(unsigned j=1;j<(nhist_[1]-1);++j){
|                    ~^~~~~~~~~~~~~~
PairOrientationalEntropyPerpendicular.QtIdmk.cpp: In member function ‘void PLMD::colvar::PairOrientationalEntropyPerpendicular::outputGofr(PLMD::Matrix<double>, const char*)’:
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:802:21: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
802 |   for(unsigned i=0;i<nhist_[0];++i){
PairOrientationalEntropyPerpendicular.QtIdmk.cpp:803:24: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
803 |      for(unsigned j=0;j<nhist_[1];++j){
</pre>
{% endraw %}
