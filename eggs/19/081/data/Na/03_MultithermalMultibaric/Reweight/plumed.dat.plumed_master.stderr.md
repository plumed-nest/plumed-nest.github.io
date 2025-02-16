**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[fv-az1112-175:69374] *** Process received signal ***
[fv-az1112-175:69374] Signal: Aborted (6)
[fv-az1112-175:69374] Signal code:  (-6)
[fv-az1112-175:69374] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2ed1045330]
[fv-az1112-175:69374] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2ed109eb2c]
[fv-az1112-175:69374] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2ed104527e]
[fv-az1112-175:69374] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2ed10288ff]
[fv-az1112-175:69374] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2ed14a5ff5]
[fv-az1112-175:69374] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2ed14bb0da]
[fv-az1112-175:69374] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2ed14a5a55]
[fv-az1112-175:69374] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2ed14a5a6f]
[fv-az1112-175:69374] [ 8] plumed_master(+0x146dd)[0x56061adda6dd]
[fv-az1112-175:69374] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2ed102a1ca]
[fv-az1112-175:69374] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2ed102a28b]
[fv-az1112-175:69374] [11] plumed_master(+0x15365)[0x56061addb365]
[fv-az1112-175:69374] *** End of error message ***
</pre>
{% endraw %}
