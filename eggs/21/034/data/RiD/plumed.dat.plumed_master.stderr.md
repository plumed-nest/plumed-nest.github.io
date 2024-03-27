**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: DEEPFE LABEL=dpfe TRUST_LVL_1=1.0 TRUST_LVL_2=2.0 MODEL=graph.pb ARG=dih-000-01,dih-001-00,dih-001-01,dih-002-00,dih-002-01,dih-003-00,dih-003-01,dih-004-00,dih-004-01,dih-005-00,dih-005-01,dih-006-00,dih-006-01,dih-007-00,dih-007-01,dih-008-00,dih-008-01,dih-009-00
Maybe a missing space or a typo?
[fv-az1210-136:70207] *** Process received signal ***
[fv-az1210-136:70207] Signal: Aborted (6)
[fv-az1210-136:70207] Signal code:  (-6)
[fv-az1210-136:70207] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc866c42520]
[fv-az1210-136:70207] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc866c969fc]
[fv-az1210-136:70207] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc866c42476]
[fv-az1210-136:70207] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc866c287f3]
[fv-az1210-136:70207] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fc8670a4f26]
[fv-az1210-136:70207] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fc8670b6d9c]
[fv-az1210-136:70207] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fc8670b6e07]
[fv-az1210-136:70207] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc8670b70bb]
[fv-az1210-136:70207] [ 8] plumed_master(+0x12e7f)[0x555c9656de7f]
[fv-az1210-136:70207] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc866c29d90]
[fv-az1210-136:70207] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc866c29e40]
[fv-az1210-136:70207] [11] plumed_master(+0x13115)[0x555c9656e115]
[fv-az1210-136:70207] *** End of error message ***
</pre>
{% endraw %}
