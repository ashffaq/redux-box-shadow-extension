# redux-box-shadow-extension
Redux Framework Box Shadow Extension

Redux Framework Box Shadow Extensio is an Extension for well known WordPress theme options framework "Redux" to create a field for Box Shadow.

<h2>Preview</h2>
<a href="https://www.youtube.com/watch?v=fsTI1jaymtA" target="_blank">
<img src="https://upload.vstanced.com/images/2017/05/04/k6s.png" 
alt="IMAGE ALT TEXT HERE" border="10" style="width: 100%;"/>
</a>


<h2>How to Include in Redux Framework?</h2>
You should have knowledge about how to install extensions in Redux Framwork.

This link may help you.
https://docs.reduxframework.com/core/advanced/loading-extensions/

<h2>Itnitialize box shadow field in theme options file</h2>
<code>
<pre>
array(         
    'id'      => 'box-shadow',
    'type'    => 'box_shadow',
    'title'   => __('Box Shadow', 'redux-framework-demo'),
    'units'   => array( 'px', 'em', 'rem' ),
    'output'  => ( '.header' ),
    'opacity' => true,
    'rgba'    => true,
    'default' => array (
        'horizontal'   => '5px', // can be negative value
        'vertical'     => '5px', // can be negative value
        'blur'         => '5px',
        'spread'       => '5px',
        'opacity'      => '1.0',
        'shadow-color' => '#f71313',
        'shadow-type'  => 'inset', // 'inset' or 'outside'
        'units'        => 'px',
    ),
),
</pre>
</code>

<h2>How to use in frontend?</h2>

You have the array of values which can be used to create the css box shadow.

<code>
<pre>
Array ( 
    [horizontal] = > 5px 
    [vertical]     => 5px
    [blur]         => 5px
    [spread]       => 5px
    [opacity]      => 1
    [units]        => px
    [shadow-color] => #f71313
    [shadow-type]  => inset
    [rgba]         => rgba(247,19,19,1)
)
</pre>
</code>
