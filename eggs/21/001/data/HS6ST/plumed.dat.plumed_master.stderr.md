**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[fv-az787-589:65766] *** Process received signal ***
[fv-az787-589:65766] Signal: Aborted (6)
[fv-az787-589:65766] Signal code:  (-6)
[fv-az787-589:65766] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd296a45330]
[fv-az787-589:65766] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd296a9eb2c]
[fv-az787-589:65766] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd296a4527e]
[fv-az787-589:65766] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd296a288ff]
[fv-az787-589:65766] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd296ea5ff5]
[fv-az787-589:65766] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd296ebb0da]
[fv-az787-589:65766] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd296ea5a55]
[fv-az787-589:65766] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd296ea5a6f]
[fv-az787-589:65766] [ 8] plumed_master(+0x146dd)[0x55cbefeab6dd]
[fv-az787-589:65766] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd296a2a1ca]
[fv-az787-589:65766] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd296a2a28b]
[fv-az787-589:65766] [11] plumed_master(+0x15365)[0x55cbefeac365]
[fv-az787-589:65766] *** End of error message ***
</pre>
{% endraw %}
