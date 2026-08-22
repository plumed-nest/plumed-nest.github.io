**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[runnervm76f27:04954] *** Process received signal ***
[runnervm76f27:04954] Signal: Aborted (6)
[runnervm76f27:04954] Signal code:  (-6)
[runnervm76f27:04954] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb102045330]
[runnervm76f27:04954] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb10209ec0c]
[runnervm76f27:04954] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb10204527e]
[runnervm76f27:04954] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1020288ff]
[runnervm76f27:04954] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1024a5ff5]
[runnervm76f27:04954] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1024bb0da]
[runnervm76f27:04954] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1024a5a55]
[runnervm76f27:04954] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1024a5a6f]
[runnervm76f27:04954] [ 8] plumed(+0x146dd)[0x55bff72716dd]
[runnervm76f27:04954] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb10202a1ca]
[runnervm76f27:04954] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb10202a28b]
[runnervm76f27:04954] [11] plumed(+0x15365)[0x55bff7272365]
[runnervm76f27:04954] *** End of error message ***
</pre>
{% endraw %}
