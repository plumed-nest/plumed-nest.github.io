**Project ID:** [plumID:19.044]({{ '/' | absolute_url }}eggs/19/044/)  
Stderr for source:  MultithermalMultibaricSimulations/MultithermalMultibaric/Analysis/SampledDistribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[fv-az1391-351:66221] *** Process received signal ***
[fv-az1391-351:66221] Signal: Aborted (6)
[fv-az1391-351:66221] Signal code:  (-6)
[fv-az1391-351:66221] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c44e45330]
[fv-az1391-351:66221] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c44e9eb2c]
[fv-az1391-351:66221] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c44e4527e]
[fv-az1391-351:66221] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c44e288ff]
[fv-az1391-351:66221] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c452a5ff5]
[fv-az1391-351:66221] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c452bb0da]
[fv-az1391-351:66221] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c452a5a55]
[fv-az1391-351:66221] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c452a5a6f]
[fv-az1391-351:66221] [ 8] plumed_master(+0x146dd)[0x55a77cf9c6dd]
[fv-az1391-351:66221] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c44e2a1ca]
[fv-az1391-351:66221] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c44e2a28b]
[fv-az1391-351:66221] [11] plumed_master(+0x15365)[0x55a77cf9d365]
[fv-az1391-351:66221] *** End of error message ***
</pre>
{% endraw %}
