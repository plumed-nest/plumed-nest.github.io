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
[fv-az1624-565:09930] *** Process received signal ***
[fv-az1624-565:09930] Signal: Aborted (6)
[fv-az1624-565:09930] Signal code:  (-6)
[fv-az1624-565:09930] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7eff4ee45330]
[fv-az1624-565:09930] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7eff4ee9eb2c]
[fv-az1624-565:09930] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7eff4ee4527e]
[fv-az1624-565:09930] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7eff4ee288ff]
[fv-az1624-565:09930] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7eff4f2a5ff5]
[fv-az1624-565:09930] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7eff4f2bb0da]
[fv-az1624-565:09930] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7eff4f2a5a55]
[fv-az1624-565:09930] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7eff4f2a5a6f]
[fv-az1624-565:09930] [ 8] plumed_master(+0x146dd)[0x55bb6e9846dd]
[fv-az1624-565:09930] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7eff4ee2a1ca]
[fv-az1624-565:09930] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7eff4ee2a28b]
[fv-az1624-565:09930] [11] plumed_master(+0x15365)[0x55bb6e985365]
[fv-az1624-565:09930] *** End of error message ***
</pre>
{% endraw %}
