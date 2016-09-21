<html><head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Exported from Notepad++</title>
<style type="text/css">
span {
	font-family: 'Courier New';
	font-size: 10pt;
	color: #000000;
}
.sc0 {
}
.sc4 {
	color: #FF8000;
}
.sc10 {
	font-weight: bold;
	color: #000080;
}
.sc11 {
}
.sc12 {
}
</style>
</head>
<body>
<div style="float: left; white-space: pre; line-height: 1; background: #FFFFFF; "><span class="sc4">1</span><span class="sc10">-</span><span class="sc11">实验目的：</span><span class="sc0">
    </span><span class="sc11">Android</span><span class="sc0"> </span><span class="sc11">NDK方式编译生成so动态库</span><span class="sc0">
</span><span class="sc4">2</span><span class="sc10">-</span><span class="sc11">开发工具：</span><span class="sc0">
    </span><span class="sc11">Notepad</span><span class="sc10">++</span><span class="sc0">
    </span><span class="sc11">android</span><span class="sc10">-</span><span class="sc11">ndk</span><span class="sc10">-</span><span class="sc11">r8b</span><span class="sc0">

</span><span class="sc4">3</span><span class="sc10">-</span><span class="sc11">工程目录：</span><span class="sc0">
    </span><span class="sc11">NDKexample1</span><span class="sc0">
        </span><span class="sc11">│</span><span class="sc0">  </span><span class="sc11">README</span><span class="sc10">.</span><span class="sc11">md</span><span class="sc0">
        </span><span class="sc11">│</span><span class="sc0">
        </span><span class="sc11">└─jni</span><span class="sc0">
             </span><span class="sc11">Android</span><span class="sc10">.</span><span class="sc11">mk</span><span class="sc0">
             </span><span class="sc11">hello</span><span class="sc10">.</span><span class="sc11">c</span><span class="sc0">
</span><span class="sc4">4</span><span class="sc10">-</span><span class="sc11">编译与运行结果：</span><span class="sc0">
    </span><span class="sc4">4.1</span><span class="sc0"> </span><span class="sc11">ndk</span><span class="sc10">-</span><span class="sc11">build</span><span class="sc0">
        </span><span class="sc11">NDKexample1</span><span class="sc0">\</span><span class="sc11">jni</span><span class="sc10">&gt;</span><span class="sc11">ndk</span><span class="sc10">-</span><span class="sc11">build</span><span class="sc0">
        </span><span class="sc12">"Compile thumb : hello &lt;= hello.c
</span><span class="sc0">        </span><span class="sc11">SharedLibrary</span><span class="sc0">  </span><span class="sc10">:</span><span class="sc0"> </span><span class="sc11">libhello</span><span class="sc10">.</span><span class="sc11">so</span><span class="sc0">
        </span><span class="sc11">Install</span><span class="sc0">        </span><span class="sc10">:</span><span class="sc0"> </span><span class="sc11">libhello</span><span class="sc10">.</span><span class="sc11">so</span><span class="sc0"> </span><span class="sc10">=&gt;</span><span class="sc0"> </span><span class="sc11">libs</span><span class="sc10">/</span><span class="sc11">armeabi</span><span class="sc10">/</span><span class="sc11">libhello</span><span class="sc10">.</span><span class="sc11">so</span><span class="sc0">
    </span><span class="sc4">4.2</span><span class="sc0"> </span><span class="sc11">libhello</span><span class="sc10">.</span><span class="sc11">so</span></div>

</body></html>
