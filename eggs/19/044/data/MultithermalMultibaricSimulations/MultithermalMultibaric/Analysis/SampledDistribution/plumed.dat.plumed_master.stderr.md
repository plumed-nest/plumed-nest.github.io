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
[fv-az1720-841:11410] *** Process received signal ***
[fv-az1720-841:11410] Signal: Aborted (6)
[fv-az1720-841:11410] Signal code:  (-6)
[fv-az1720-841:11410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f68ab245330]
[fv-az1720-841:11410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f68ab29eb2c]
[fv-az1720-841:11410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f68ab24527e]
[fv-az1720-841:11410] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68ab2288ff]
[fv-az1720-841:11410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68ab6a5ff5]
[fv-az1720-841:11410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68ab6bb0da]
[fv-az1720-841:11410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68ab6a5a55]
[fv-az1720-841:11410] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68ab6a5a6f]
[fv-az1720-841:11410] [ 8] plumed_master(+0x146dd)[0x563b2096a6dd]
[fv-az1720-841:11410] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f68ab22a1ca]
[fv-az1720-841:11410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f68ab22a28b]
[fv-az1720-841:11410] [11] plumed_master(+0x15365)[0x563b2096b365]
[fv-az1720-841:11410] *** End of error message ***
</pre>
{% endraw %}
