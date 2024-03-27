**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCE_FROM_CONTOUR with label cont : keyword DATA is compulsory for this action
[fv-az1153-362:71896] *** Process received signal ***
[fv-az1153-362:71896] Signal: Aborted (6)
[fv-az1153-362:71896] Signal code:  (-6)
[fv-az1153-362:71896] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe4a3842520]
[fv-az1153-362:71896] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe4a38969fc]
[fv-az1153-362:71896] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe4a3842476]
[fv-az1153-362:71896] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe4a38287f3]
[fv-az1153-362:71896] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fe4a3ca4f26]
[fv-az1153-362:71896] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fe4a3cb6d9c]
[fv-az1153-362:71896] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fe4a3cb6e07]
[fv-az1153-362:71896] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe4a3cb70bb]
[fv-az1153-362:71896] [ 8] plumed(+0x12f48)[0x560cc8f1af48]
[fv-az1153-362:71896] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe4a3829d90]
[fv-az1153-362:71896] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe4a3829e40]
[fv-az1153-362:71896] [11] plumed(+0x131e5)[0x560cc8f1b1e5]
[fv-az1153-362:71896] *** End of error message ***
</pre>
{% endraw %}
