**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[fv-az1440-40:61783] *** Process received signal ***
[fv-az1440-40:61783] Signal: Aborted (6)
[fv-az1440-40:61783] Signal code:  (-6)
[fv-az1440-40:61783] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5836845330]
[fv-az1440-40:61783] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f583689eb2c]
[fv-az1440-40:61783] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f583684527e]
[fv-az1440-40:61783] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58368288ff]
[fv-az1440-40:61783] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5836ca5ff5]
[fv-az1440-40:61783] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5836cbb0da]
[fv-az1440-40:61783] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5836ca5a55]
[fv-az1440-40:61783] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5836ca5a6f]
[fv-az1440-40:61783] [ 8] plumed(+0x146dd)[0x55962bf2f6dd]
[fv-az1440-40:61783] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f583682a1ca]
[fv-az1440-40:61783] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f583682a28b]
[fv-az1440-40:61783] [11] plumed(+0x15365)[0x55962bf30365]
[fv-az1440-40:61783] *** End of error message ***
</pre>
{% endraw %}
