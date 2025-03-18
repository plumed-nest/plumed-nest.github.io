**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @94 : keyword ARG is compulsory for this action
[fv-az790-36:62830] *** Process received signal ***
[fv-az790-36:62830] Signal: Aborted (6)
[fv-az790-36:62830] Signal code:  (-6)
[fv-az790-36:62830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb56ee45330]
[fv-az790-36:62830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb56ee9eb2c]
[fv-az790-36:62830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb56ee4527e]
[fv-az790-36:62830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb56ee288ff]
[fv-az790-36:62830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb56f2a5ff5]
[fv-az790-36:62830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb56f2bb0da]
[fv-az790-36:62830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb56f2a5a55]
[fv-az790-36:62830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb56f2a5a6f]
[fv-az790-36:62830] [ 8] plumed_master(+0x146dd)[0x5651090d06dd]
[fv-az790-36:62830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb56ee2a1ca]
[fv-az790-36:62830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb56ee2a28b]
[fv-az790-36:62830] [11] plumed_master(+0x15365)[0x5651090d1365]
[fv-az790-36:62830] *** End of error message ***
</pre>
{% endraw %}
