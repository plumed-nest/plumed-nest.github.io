**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[runnervm76f27:11610] *** Process received signal ***
[runnervm76f27:11610] Signal: Aborted (6)
[runnervm76f27:11610] Signal code:  (-6)
[runnervm76f27:11610] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa43c445330]
[runnervm76f27:11610] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa43c49ec0c]
[runnervm76f27:11610] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa43c44527e]
[runnervm76f27:11610] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa43c4288ff]
[runnervm76f27:11610] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa43c8a5ff5]
[runnervm76f27:11610] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa43c8bb0da]
[runnervm76f27:11610] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa43c8a5a55]
[runnervm76f27:11610] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa43c8a5a6f]
[runnervm76f27:11610] [ 8] plumed_master(+0x146dd)[0x55a9fbfa16dd]
[runnervm76f27:11610] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa43c42a1ca]
[runnervm76f27:11610] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa43c42a28b]
[runnervm76f27:11610] [11] plumed_master(+0x15365)[0x55a9fbfa2365]
[runnervm76f27:11610] *** End of error message ***
</pre>
{% endraw %}
