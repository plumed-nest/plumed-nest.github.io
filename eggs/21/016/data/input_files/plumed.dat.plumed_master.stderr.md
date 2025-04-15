**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[fv-az802-713:65377] *** Process received signal ***
[fv-az802-713:65377] Signal: Aborted (6)
[fv-az802-713:65377] Signal code:  (-6)
[fv-az802-713:65377] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe3d7a45330]
[fv-az802-713:65377] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe3d7a9eb2c]
[fv-az802-713:65377] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe3d7a4527e]
[fv-az802-713:65377] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3d7a288ff]
[fv-az802-713:65377] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3d7ea5ff5]
[fv-az802-713:65377] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3d7ebb0da]
[fv-az802-713:65377] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3d7ea5a55]
[fv-az802-713:65377] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3d7ea5a6f]
[fv-az802-713:65377] [ 8] plumed_master(+0x146dd)[0x55abea8a46dd]
[fv-az802-713:65377] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe3d7a2a1ca]
[fv-az802-713:65377] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe3d7a2a28b]
[fv-az802-713:65377] [11] plumed_master(+0x15365)[0x55abea8a5365]
[fv-az802-713:65377] *** End of error message ***
</pre>
{% endraw %}
