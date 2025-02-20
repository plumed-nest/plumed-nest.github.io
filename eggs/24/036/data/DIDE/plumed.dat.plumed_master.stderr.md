**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az816-356:05380] *** Process received signal ***
[fv-az816-356:05380] Signal: Aborted (6)
[fv-az816-356:05380] Signal code:  (-6)
[fv-az816-356:05380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2f1a45330]
[fv-az816-356:05380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2f1a9eb2c]
[fv-az816-356:05380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2f1a4527e]
[fv-az816-356:05380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2f1a288ff]
[fv-az816-356:05380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2f1ea5ff5]
[fv-az816-356:05380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2f1ebb0da]
[fv-az816-356:05380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2f1ea5a55]
[fv-az816-356:05380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2f1ea5a6f]
[fv-az816-356:05380] [ 8] plumed_master(+0x146dd)[0x559c870e56dd]
[fv-az816-356:05380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2f1a2a1ca]
[fv-az816-356:05380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2f1a2a28b]
[fv-az816-356:05380] [11] plumed_master(+0x15365)[0x559c870e6365]
[fv-az816-356:05380] *** End of error message ***
</pre>
{% endraw %}
