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
[fv-az1344-582:67971] *** Process received signal ***
[fv-az1344-582:67971] Signal: Aborted (6)
[fv-az1344-582:67971] Signal code:  (-6)
[fv-az1344-582:67971] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f969ea45330]
[fv-az1344-582:67971] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f969ea9eb2c]
[fv-az1344-582:67971] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f969ea4527e]
[fv-az1344-582:67971] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f969ea288ff]
[fv-az1344-582:67971] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f969eea5ff5]
[fv-az1344-582:67971] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f969eebb0da]
[fv-az1344-582:67971] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f969eea5a55]
[fv-az1344-582:67971] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f969eea5a6f]
[fv-az1344-582:67971] [ 8] plumed_master(+0x146dd)[0x560f1d37d6dd]
[fv-az1344-582:67971] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f969ea2a1ca]
[fv-az1344-582:67971] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f969ea2a28b]
[fv-az1344-582:67971] [11] plumed_master(+0x15365)[0x560f1d37e365]
[fv-az1344-582:67971] *** End of error message ***
</pre>
{% endraw %}
