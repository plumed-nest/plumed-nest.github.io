**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:476) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[fv-az1657-925:09536] *** Process received signal ***
[fv-az1657-925:09536] Signal: Aborted (6)
[fv-az1657-925:09536] Signal code:  (-6)
[fv-az1657-925:09536] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6786445330]
[fv-az1657-925:09536] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f678649eb2c]
[fv-az1657-925:09536] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f678644527e]
[fv-az1657-925:09536] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67864288ff]
[fv-az1657-925:09536] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67868a5ff5]
[fv-az1657-925:09536] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67868bb0da]
[fv-az1657-925:09536] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67868a5a55]
[fv-az1657-925:09536] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67868a5a6f]
[fv-az1657-925:09536] [ 8] plumed_master(+0x146dd)[0x55bc314e96dd]
[fv-az1657-925:09536] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f678642a1ca]
[fv-az1657-925:09536] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f678642a28b]
[fv-az1657-925:09536] [11] plumed_master(+0x15365)[0x55bc314ea365]
[fv-az1657-925:09536] *** End of error message ***
</pre>
{% endraw %}
