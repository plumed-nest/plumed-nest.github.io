**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:168) void PLMD::Keywords::use(const string&)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[fv-az1215-275:08287] *** Process received signal ***
[fv-az1215-275:08287] Signal: Aborted (6)
[fv-az1215-275:08287] Signal code:  (-6)
[fv-az1215-275:08287] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc1f4e42520]
[fv-az1215-275:08287] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc1f4e969fc]
[fv-az1215-275:08287] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc1f4e42476]
[fv-az1215-275:08287] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc1f4e287f3]
[fv-az1215-275:08287] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc1f52a2b9e]
[fv-az1215-275:08287] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc1f52ae20c]
[fv-az1215-275:08287] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc1f52ae277]
[fv-az1215-275:08287] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc1f52ae52b]
[fv-az1215-275:08287] [ 8] plumed_master(+0x14254)[0x55dcfa8cf254]
[fv-az1215-275:08287] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc1f4e29d90]
[fv-az1215-275:08287] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc1f4e29e40]
[fv-az1215-275:08287] [11] plumed_master(+0x14eb5)[0x55dcfa8cfeb5]
[fv-az1215-275:08287] *** End of error message ***
</pre>
{% endraw %}
