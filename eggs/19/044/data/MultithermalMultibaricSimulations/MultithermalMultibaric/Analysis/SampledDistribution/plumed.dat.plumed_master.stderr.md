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
[fv-az1360-658:10412] *** Process received signal ***
[fv-az1360-658:10412] Signal: Aborted (6)
[fv-az1360-658:10412] Signal code:  (-6)
[fv-az1360-658:10412] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdeb3445330]
[fv-az1360-658:10412] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdeb349eb2c]
[fv-az1360-658:10412] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdeb344527e]
[fv-az1360-658:10412] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdeb34288ff]
[fv-az1360-658:10412] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdeb38a5ff5]
[fv-az1360-658:10412] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdeb38bb0da]
[fv-az1360-658:10412] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdeb38a5a55]
[fv-az1360-658:10412] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdeb38a5a6f]
[fv-az1360-658:10412] [ 8] plumed_master(+0x146dd)[0x562344c7f6dd]
[fv-az1360-658:10412] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdeb342a1ca]
[fv-az1360-658:10412] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdeb342a28b]
[fv-az1360-658:10412] [11] plumed_master(+0x15365)[0x562344c80365]
[fv-az1360-658:10412] *** End of error message ***
</pre>
{% endraw %}
