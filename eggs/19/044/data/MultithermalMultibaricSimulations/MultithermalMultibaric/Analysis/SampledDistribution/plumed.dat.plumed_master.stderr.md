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
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[fv-az1280-696:13922] *** Process received signal ***
[fv-az1280-696:13922] Signal: Aborted (6)
[fv-az1280-696:13922] Signal code:  (-6)
[fv-az1280-696:13922] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b68a45330]
[fv-az1280-696:13922] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b68a9eb2c]
[fv-az1280-696:13922] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b68a4527e]
[fv-az1280-696:13922] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b68a288ff]
[fv-az1280-696:13922] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b68ea5ff5]
[fv-az1280-696:13922] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b68ebb0da]
[fv-az1280-696:13922] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b68ea5a55]
[fv-az1280-696:13922] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b68ea5a6f]
[fv-az1280-696:13922] [ 8] plumed_master(+0x146dd)[0x55ead41d96dd]
[fv-az1280-696:13922] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b68a2a1ca]
[fv-az1280-696:13922] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b68a2a28b]
[fv-az1280-696:13922] [11] plumed_master(+0x15365)[0x55ead41da365]
[fv-az1280-696:13922] *** End of error message ***
</pre>
{% endraw %}
