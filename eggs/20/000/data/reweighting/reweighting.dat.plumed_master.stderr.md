**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[fv-az1657-925:10956] *** Process received signal ***
[fv-az1657-925:10956] Signal: Aborted (6)
[fv-az1657-925:10956] Signal code:  (-6)
[fv-az1657-925:10956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9ddf445330]
[fv-az1657-925:10956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9ddf49eb2c]
[fv-az1657-925:10956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9ddf44527e]
[fv-az1657-925:10956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9ddf4288ff]
[fv-az1657-925:10956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9ddf8a5ff5]
[fv-az1657-925:10956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9ddf8bb0da]
[fv-az1657-925:10956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9ddf8a5a55]
[fv-az1657-925:10956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9ddf8a5a6f]
[fv-az1657-925:10956] [ 8] plumed_master(+0x146dd)[0x558f8243d6dd]
[fv-az1657-925:10956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9ddf42a1ca]
[fv-az1657-925:10956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9ddf42a28b]
[fv-az1657-925:10956] [11] plumed_master(+0x15365)[0x558f8243e365]
[fv-az1657-925:10956] *** End of error message ***
</pre>
{% endraw %}
