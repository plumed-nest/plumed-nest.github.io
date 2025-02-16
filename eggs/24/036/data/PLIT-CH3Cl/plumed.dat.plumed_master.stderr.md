**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[fv-az787-589:60517] *** Process received signal ***
[fv-az787-589:60517] Signal: Aborted (6)
[fv-az787-589:60517] Signal code:  (-6)
[fv-az787-589:60517] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe1c7845330]
[fv-az787-589:60517] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe1c789eb2c]
[fv-az787-589:60517] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe1c784527e]
[fv-az787-589:60517] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe1c78288ff]
[fv-az787-589:60517] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe1c7ca5ff5]
[fv-az787-589:60517] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe1c7cbb0da]
[fv-az787-589:60517] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe1c7ca5a55]
[fv-az787-589:60517] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe1c7ca5a6f]
[fv-az787-589:60517] [ 8] plumed_master(+0x146dd)[0x557a471c26dd]
[fv-az787-589:60517] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe1c782a1ca]
[fv-az787-589:60517] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe1c782a28b]
[fv-az787-589:60517] [11] plumed_master(+0x15365)[0x557a471c3365]
[fv-az787-589:60517] *** End of error message ***
</pre>
{% endraw %}
