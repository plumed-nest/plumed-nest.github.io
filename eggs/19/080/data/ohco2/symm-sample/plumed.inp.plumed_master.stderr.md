**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az1979-234:66921] *** Process received signal ***
[fv-az1979-234:66921] Signal: Aborted (6)
[fv-az1979-234:66921] Signal code:  (-6)
[fv-az1979-234:66921] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd7b4a45330]
[fv-az1979-234:66921] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd7b4a9eb2c]
[fv-az1979-234:66921] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd7b4a4527e]
[fv-az1979-234:66921] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7b4a288ff]
[fv-az1979-234:66921] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7b4ea5ff5]
[fv-az1979-234:66921] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7b4ebb0da]
[fv-az1979-234:66921] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7b4ea5a55]
[fv-az1979-234:66921] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7b4ea5a6f]
[fv-az1979-234:66921] [ 8] plumed_master(+0x146dd)[0x55c5384106dd]
[fv-az1979-234:66921] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd7b4a2a1ca]
[fv-az1979-234:66921] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd7b4a2a28b]
[fv-az1979-234:66921] [11] plumed_master(+0x15365)[0x55c538411365]
[fv-az1979-234:66921] *** End of error message ***
</pre>
{% endraw %}
