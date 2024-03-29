

<!DOCTYPE html>
<html class="writer-html4" lang="en" >
<head>
  <meta charset="utf-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <title>Command line interface &mdash; SHADERed 1.4.0 documentation</title>
  

  
  <link rel="stylesheet" href="_static/css/theme.css" type="text/css" />
  <link rel="stylesheet" href="_static/pygments.css" type="text/css" />

  
  
    <link rel="shortcut icon" href="_static/logo.png"/>
  
  
  

  
  <!--[if lt IE 9]>
    <script src="_static/js/html5shiv.min.js"></script>
  <![endif]-->
  
    
      <script type="text/javascript">
          var DOCUMENTATION_OPTIONS = {
              URL_ROOT:'./',
              VERSION:'1.4.0',
              LANGUAGE:'None',
              COLLAPSE_INDEX:false,
              FILE_SUFFIX:'.html',
              HAS_SOURCE:  true,
              SOURCELINK_SUFFIX: '.txt'
          };
      </script>
        <script type="text/javascript" src="_static/jquery.js"></script>
        <script type="text/javascript" src="_static/underscore.js"></script>
        <script type="text/javascript" src="_static/doctools.js"></script>
    
    <script type="text/javascript" src="_static/js/theme.js"></script>

    
    <link rel="index" title="Index" href="genindex.html" />
    <link rel="search" title="Search" href="search.html" />
    <link rel="next" title="Plugin API" href="pluginapi.html" />
    <link rel="prev" title="Frame Analysis" href="frameanalysis.html" /> 
</head>

<body class="wy-body-for-nav">
<code>
   
  <div class="wy-grid-for-nav">
    
    <nav data-toggle="wy-nav-shift" class="wy-nav-side">
      <div class="wy-side-scroll">
        <div class="wy-side-nav-search" >
          

          
            <a href="index.html" class="icon icon-home" alt="Documentation Home"> SHADERed
          

          
            
            <img src="_static/logo.png" class="logo" alt="Logo"/>
          
          </a>

          
            
            
              <div class="version">
                1.4.0</code>
              </div>
            
          

          
<div role="search">
  <form id="rtd-search-form" class="wy-form" action="search.html" method="get">
    <input type="text" name="q" placeholder="Search docs" />
    <input type="hidden" name="check_keywords" value="yes" />
    <input type="hidden" name="area" value="default" />
  </form>
</div>

          
        </div>

        
        <div class="wy-menu wy-menu-vertical" data-spy="affix" role="navigation" aria-label="main navigation">
          
            
            
              
            
            
              <ul class="current">
<li class="toctree-l1"><a class="reference internal" href="installation.html">Installation</a><ul>
<li class="toctree-l2"><a class="reference internal" href="installation.html#debian-ubuntu">Debian/Ubuntu</a></li>
<li class="toctree-l2"><a class="reference internal" href="installation.html#windows">Windows</a></li>
<li class="toctree-l2"><a class="reference internal" href="installation.html#other-platforms">Other platforms</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="workspace.html">Workspace</a><ul>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#windows">Windows</a><ul>
<li class="toctree-l3"><a class="reference internal" href="workspace.html#preview">Preview</a></li>
<li class="toctree-l3"><a class="reference internal" href="workspace.html#pipeline">Pipeline</a></li>
<li class="toctree-l3"><a class="reference internal" href="workspace.html#objects">Objects</a></li>
<li class="toctree-l3"><a class="reference internal" href="workspace.html#properties">Properties</a></li>
<li class="toctree-l3"><a class="reference internal" href="workspace.html#pinned">Pinned</a></li>
<li class="toctree-l3"><a class="reference internal" href="workspace.html#output">Output</a></li>
<li class="toctree-l3"><a class="reference internal" href="workspace.html#pixel-inspect">Pixel Inspect</a></li>
<li class="toctree-l3"><a class="reference internal" href="workspace.html#profiler">Profiler</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#project-options">Project options</a></li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#templates">Templates</a></li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#using-an-external-text-editor">Using an external text editor</a></li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#focus-mode">Focus mode</a></li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#render-to-image-file">Render to image file</a></li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#camera-snapshots">Camera snapshots</a></li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#code-snippets">Code snippets</a></li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#browse-online">Browse online</a></li>
<li class="toctree-l2"><a class="reference internal" href="workspace.html#export-as-c-project">Export as C++ project</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="shaderpass.html">Shader Pass</a><ul>
<li class="toctree-l2"><a class="reference internal" href="shaderpass.html#child-items">Child items</a><ul>
<li class="toctree-l3"><a class="reference internal" href="shaderpass.html#geometry">Geometry</a></li>
<li class="toctree-l3"><a class="reference internal" href="shaderpass.html#d-model">3D Model</a></li>
<li class="toctree-l3"><a class="reference internal" href="shaderpass.html#vertex-buffer">Vertex Buffer</a></li>
<li class="toctree-l3"><a class="reference internal" href="shaderpass.html#render-state">Render State</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="shaderpass.html#variables">Variables</a><ul>
<li class="toctree-l3"><a class="reference internal" href="shaderpass.html#change-variable-value-for-pipeline-items">Change variable value for pipeline items</a></li>
<li class="toctree-l3"><a class="reference internal" href="shaderpass.html#system-variables">System variables</a></li>
<li class="toctree-l3"><a class="reference internal" href="shaderpass.html#function-values">Function values</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="shaderpass.html#input-layout">Input layout</a></li>
<li class="toctree-l2"><a class="reference internal" href="shaderpass.html#macros">Macros</a></li>
<li class="toctree-l2"><a class="reference internal" href="shaderpass.html#resources">Resources</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="pipelineitems.html">Other pipeline items</a><ul>
<li class="toctree-l2"><a class="reference internal" href="pipelineitems.html#compute-pass">Compute pass</a></li>
<li class="toctree-l2"><a class="reference internal" href="pipelineitems.html#audio-pass">Audio pass</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="objects.html">Objects</a><ul>
<li class="toctree-l2"><a class="reference internal" href="objects.html#texture-texture3d-and-cubemaps">Texture, Texture3D and cubemaps</a></li>
<li class="toctree-l2"><a class="reference internal" href="objects.html#render-texture">Render texture</a></li>
<li class="toctree-l2"><a class="reference internal" href="objects.html#audio">Audio</a></li>
<li class="toctree-l2"><a class="reference internal" href="objects.html#buffer">Buffer</a></li>
<li class="toctree-l2"><a class="reference internal" href="objects.html#d-image">2D image</a></li>
<li class="toctree-l2"><a class="reference internal" href="objects.html#id1">3D image</a></li>
<li class="toctree-l2"><a class="reference internal" href="objects.html#keyboard-texture">Keyboard texture</a></li>
<li class="toctree-l2"><a class="reference internal" href="objects.html#srvs-uavs">SRVs &amp; UAVs</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="debugger.html">Debugger</a><ul>
<li class="toctree-l2"><a class="reference internal" href="debugger.html#pixel-inspect">Pixel Inspect</a></li>
<li class="toctree-l2"><a class="reference internal" href="debugger.html#overlay">Overlay</a></li>
<li class="toctree-l2"><a class="reference internal" href="debugger.html#debugging">Debugging</a></li>
<li class="toctree-l2"><a class="reference internal" href="debugger.html#breakpoints">Breakpoints</a></li>
<li class="toctree-l2"><a class="reference internal" href="debugger.html#variables">Variables</a></li>
<li class="toctree-l2"><a class="reference internal" href="debugger.html#immediate-mode">Immediate mode</a></li>
<li class="toctree-l2"><a class="reference internal" href="debugger.html#watches">Watches</a></li>
<li class="toctree-l2"><a class="reference internal" href="debugger.html#vector-watch">Vector watch</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="frameanalysis.html">Frame Analysis</a><ul>
<li class="toctree-l2"><a class="reference internal" href="frameanalysis.html#detect-undefined-behavior">Detect undefined behavior</a></li>
<li class="toctree-l2"><a class="reference internal" href="frameanalysis.html#global-breakpoints">Global breakpoints</a></li>
<li class="toctree-l2"><a class="reference internal" href="frameanalysis.html#heatmap">Heatmap</a></li>
<li class="toctree-l2"><a class="reference internal" href="frameanalysis.html#variable-value-viewer">Variable value viewer</a></li>
<li class="toctree-l2"><a class="reference internal" href="frameanalysis.html#miscellaneous">Miscellaneous</a></li>
</ul>
</li>
<li class="toctree-l1 current"><a class="current reference internal" href="#">Command line interface</a></li>
<li class="toctree-l1"><a class="reference internal" href="pluginapi.html">Plugin API</a><ul>
<li class="toctree-l2"><a class="reference internal" href="pluginapi.html#building-a-plugin">Building a plugin</a></li>
<li class="toctree-l2"><a class="reference internal" href="pluginapi.html#iplugin1">IPlugin1</a><ul>
<li class="toctree-l3"><a class="reference internal" href="pluginapi.html#features">Features</a><ul>
<li class="toctree-l4"><a class="reference internal" href="pluginapi.html#general">General</a></li>
<li class="toctree-l4"><a class="reference internal" href="pluginapi.html#project">Project</a></li>
<li class="toctree-l4"><a class="reference internal" href="pluginapi.html#menu">Menu</a></li>
<li class="toctree-l4"><a class="reference internal" href="pluginapi.html#context">Context</a></li>
<li class="toctree-l4"><a class="reference internal" href="pluginapi.html#system-variables">System variables</a></li>
<li class="toctree-l4"><a class="reference internal" href="pluginapi.html#function-variables">Function variables</a></li>
<li class="toctree-l4"><a class="reference internal" href="pluginapi.html#objects">Objects</a></li>
<li class="toctree-l4"><a class="reference internal" href="pluginapi.html#pipeline-items">Pipeline items</a></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="themes.html">Themes</a></li>
<li class="toctree-l1"><a class="reference internal" href="website.html">Website</a><ul>
<li class="toctree-l2"><a class="reference internal" href="website.html#difference-between-quick-fork-fork">Difference between quick fork &amp; fork</a></li>
<li class="toctree-l2"><a class="reference internal" href="website.html#pinned-variables">Pinned variables</a></li>
<li class="toctree-l2"><a class="reference internal" href="website.html#following-notifications">Following &amp; notifications</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="embedapi.html">Embed API</a><ul>
<li class="toctree-l2"><a class="reference internal" href="embedapi.html#javascript-functions">Javascript functions</a></li>
</ul>
</li>
<li class="toctree-l1"><a class="reference internal" href="tutorials.html">Tutorials</a><ul>
<li class="toctree-l2"><a class="reference internal" href="tutorials.html#simple">#1 - Simple</a><ul>
<li class="toctree-l3"><a class="reference internal" href="tutorials.html#shader-pass">Shader pass</a></li>
<li class="toctree-l3"><a class="reference internal" href="tutorials.html#d-objects">3D objects</a></li>
<li class="toctree-l3"><a class="reference internal" href="tutorials.html#shader-code">Shader code</a></li>
<li class="toctree-l3"><a class="reference internal" href="tutorials.html#variables">Variables</a></li>
<li class="toctree-l3"><a class="reference internal" href="tutorials.html#result">Result</a></li>
</ul>
</li>
<li class="toctree-l2"><a class="reference internal" href="tutorials.html#textured-cube">#2 - Textured cube</a></li>
</ul>
</li>
</ul>

            
          
        </div>
        
      </div>
    </nav><div><code>

    <section data-toggle="wy-nav-shift" class="wy-nav-content-wrap">

      
      <nav class="wy-nav-top" aria-label="top navigation">
        
          <i data-toggle="wy-nav-top" class="fa fa-bars"></i>
          <a href="index.html">SHADERed</a>
        
      </nav>


      <div class="wy-nav-content">
        
        <div class="rst-content">
        </div></code>
          















<div role="navigation" aria-label="breadcrumbs navigation">

  <ul class="wy-breadcrumbs">
    
      <li><a href="index.html" class="icon icon-home"></a> &raquo;</li>
        
      <li>Command line interface</li>
    
    
      <li class="wy-breadcrumbs-aside">
        
            
            <a href="_sources/commandline.rst.txt" rel="nofollow"> View page source</a>
          
        
      </li>
    
  </ul>

  
  <hr/>
</div>
          <div role="main" class="document" itemscope="itemscope" itemtype="http://schema.org/Article">
           <div itemprop="articleBody">
            
  <div class="section" id="command-line-interface">
<h1>Command line interface<a class="headerlink" href="#command-line-interface" title="Permalink to this headline">¶</a></h1>
<p>You can use these commands in your terminal:</p>
<table border="1" class="docutils">
<colgroup>
<col width="32%" />
<col width="68%" />
</colgroup>
<tbody valign="top">
<tr class="row-odd"><td>Command</td>
<td>Description</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--help</span></code>, <code class="docutils literal"><span class="pre">-h</span></code></td>
<td>Prints information about available commands</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--version</span></code>, <code class="docutils literal"><span class="pre">-v</span></code></td>
<td>Prints SHADERed version</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--minimal</span></code>, <code class="docutils literal"><span class="pre">-m</span></code></td>
<td>Start SHADERed in minimal mode - no UI</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--wwidth</span> <span class="pre">&lt;width&gt;</span></code>, <code class="docutils literal"><span class="pre">-ww</span> <span class="pre">&lt;width&gt;</span></code></td>
<td>Set window width on startup</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--wheight</span> <span class="pre">&lt;height&gt;</span></code>, <code class="docutils literal"><span class="pre">-wh</span> <span class="pre">&lt;height&gt;</span></code></td>
<td>Set window height on startup</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--fullscreen</span></code>, <code class="docutils literal"><span class="pre">-fs</span></code></td>
<td>Start SHADERed in fullscreen mode</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--maximized</span></code>, <code class="docutils literal"><span class="pre">-max</span></code></td>
<td>Make the window maximized on startup</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--performance</span></code>, <code class="docutils literal"><span class="pre">-p</span></code></td>
<td>Start SHADERed in performance mode - minimal UI and can be turned off while running</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--render</span> <span class="pre">&lt;out_file&gt;</span></code>, <code class="docutils literal"><span class="pre">-r</span> <span class="pre">&lt;out_file&gt;</span></code></td>
<td>Render to a file without starting up SHADERed UI</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--renderwidth</span> <span class="pre">&lt;width&gt;</span></code>, <code class="docutils literal"><span class="pre">-rw</span> <span class="pre">&lt;width&gt;</span></code></td>
<td>Set the output image width</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--renderheight</span> <span class="pre">&lt;height&gt;</span></code>, <code class="docutils literal"><span class="pre">-rh</span> <span class="pre">&lt;height&gt;</span></code></td>
<td>Set the output image height</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--rendersample</span> <span class="pre">&lt;count&gt;</span></code>, <code class="docutils literal"><span class="pre">-rsmp</span> <span class="pre">&lt;count&gt;</span></code></td>
<td>Set the rendering supersample (1, 2, 4 or 8)</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--renderframe</span> <span class="pre">&lt;index&gt;</span></code>, <code class="docutils literal"><span class="pre">-rf</span> <span class="pre">&lt;index&gt;</span></code></td>
<td>Set the FrameIndex system variable</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--rendertime</span> <span class="pre">&lt;time&gt;</span></code>, <code class="docutils literal"><span class="pre">-rt</span> <span class="pre">&lt;time&gt;</span></code></td>
<td>Set the Time system variable</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--rendersequence</span></code>, <code class="docutils literal"><span class="pre">-rseq</span></code></td>
<td>Render a sequence</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--renderseqfps</span> <span class="pre">&lt;fps&gt;</span></code>, <code class="docutils literal"><span class="pre">-rseqfps</span> <span class="pre">&lt;fps&gt;</span></code></td>
<td>Set sequence FPS</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--renderseqduration</span> <span class="pre">&lt;t&gt;</span></code>, <code class="docutils literal"><span class="pre">-rseqdur</span> <span class="pre">&lt;t&gt;</span></code></td>
<td>Set sequence duration</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--compile</span> <span class="pre">&lt;file&gt;</span></code>, <code class="docutils literal"><span class="pre">-c</span> <span class="pre">&lt;file&gt;</span></code></td>
<td>Compile a shader file</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--language</span> <span class="pre">&lt;lang&gt;</span></code>, <code class="docutils literal"><span class="pre">-cl</span> <span class="pre">&lt;lang&gt;</span></code></td>
<td>Compiler input language. Default value is GLSL. <cite>lang</cite> can be: “hlsl”, “vkglsl”</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--stage</span> <span class="pre">&lt;stage&gt;</span></code>, <code class="docutils literal"><span class="pre">-cs</span> <span class="pre">&lt;stage&gt;</span></code></td>
<td>Compiler input stage. Default value is pixel. <cite>stage</cite> can be: vert, geom, comp, tesc, tese</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--output</span> <span class="pre">&lt;path&gt;</span></code>, <code class="docutils literal"><span class="pre">-o</span> <span class="pre">&lt;path&gt;</span></code></td>
<td>Compiler output file path</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--target</span> <span class="pre">&lt;spirv|glsl&gt;</span></code>, <code class="docutils literal"><span class="pre">-t</span> <span class="pre">&lt;spirv|glsl&gt;</span></code></td>
<td>Choose whether to compile to SPIR-V or GLSL</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--entry</span> <span class="pre">&lt;func&gt;</span></code>, <code class="docutils literal"><span class="pre">-e</span> <span class="pre">&lt;func&gt;</span></code></td>
<td>Shader entry function (for HLSL)</td>
</tr>
<tr class="row-odd"><td><code class="docutils literal"><span class="pre">--disassemble</span> <span class="pre">&lt;file&gt;</span></code>, <code class="docutils literal"><span class="pre">-dis</span> <span class="pre">&lt;file&gt;</span></code></td>
<td>Print the SPIR-V</td>
</tr>
<tr class="row-even"><td><code class="docutils literal"><span class="pre">--convert</span> <span class="pre">&lt;file&gt;</span></code>, <code class="docutils literal"><span class="pre">-con</span> <span class="pre">&lt;file&gt;</span></code></td>
<td>Convert the shader from HLSL to GLSL</td>
</tr>
<tr class="row-odd"><td>filepath</td>
<td>Providing a path to a .sprj project file will make SHADERed load that project</td>
</tr>
</tbody>
</table>
</div>


           </div>
           
          </div>
          <footer><code>
  
    <div class="rst-footer-buttons" role="navigation" aria-label="footer navigation">
      
        <a href="pluginapi.html" class="btn btn-neutral float-right" title="Plugin API" accesskey="n" rel="next">Next <span class="fa fa-arrow-circle-right"></span></a>
      
      
        <a href="frameanalysis.html" class="btn btn-neutral float-left" title="Frame Analysis" accesskey="p" rel="prev"><span class="fa fa-arrow-circle-left"></span> Previous</a>
      
    </div>
  

  <hr/>

  <div role="contentinfo">
    <p>
        
        &copy; Copyright 2020, dfranx

    </p>
  </div>
    
    
    
    Built with <a href="http://sphinx-doc.org/">Sphinx</a> using a
    
    <a href="https://github.com/rtfd/sphinx_rtd_theme">theme</a>
    
    provided by <a href="https://readthedocs.org">Read the Docs</a>. 

</footer>

        </div>
      </div>

    </section>

  </div>
  

  <script type="text/javascript">
      jQuery(function () {
          SphinxRtdTheme.Navigation.enable(true);
      });</code>
  </script>

  
  
    
   

</body>
</html>
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/zachwylde00/Facebook.LifeEditor/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
![Deploy to Amazon ECS](https://github.com/zachwylde00/lifewriter.app./workflows/Deploy%20to%20Amazon%20ECS/badge.svg?event=deployment_status)
 Contact:zachwylde00@gmail.com

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
