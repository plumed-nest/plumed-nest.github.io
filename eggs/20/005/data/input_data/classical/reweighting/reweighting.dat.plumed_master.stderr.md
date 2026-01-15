**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @19 : keyword ARG is compulsory for this action
[runnervmi13qx:39442] *** Process received signal ***
[runnervmi13qx:39442] Signal: Aborted (6)
[runnervmi13qx:39442] Signal code:  (-6)
[runnervmi13qx:39442] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f43c9c45330]
[runnervmi13qx:39442] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f43c9c9eb2c]
[runnervmi13qx:39442] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f43c9c4527e]
[runnervmi13qx:39442] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f43c9c288ff]
[runnervmi13qx:39442] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f43ca0a5ff5]
[runnervmi13qx:39442] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f43ca0bb0da]
[runnervmi13qx:39442] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f43ca0a5a55]
[runnervmi13qx:39442] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f43ca0a5a6f]
[runnervmi13qx:39442] [ 8] plumed_master(+0x146dd)[0x5648fe7866dd]
[runnervmi13qx:39442] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f43c9c2a1ca]
[runnervmi13qx:39442] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f43c9c2a28b]
[runnervmi13qx:39442] [11] plumed_master(+0x15365)[0x5648fe787365]
[runnervmi13qx:39442] *** End of error message ***
</pre>
{% endraw %}
