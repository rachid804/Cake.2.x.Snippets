##FORM HELPER
fc<pre><?php echo $this->Form->create('Model', ); ?> </pre>
fi<pre><?php echo $this->Form->input('fielName', array('label'=>'custom label'))); ?> </pre>
fs<pre><?php
		$options = array(
			    		array('name'=>'name', 'value'=>'value' )
			    		);
		$attributes =array('key'=>'value');
		echo $this->Form->select('fieldName', $options, $attributes);
		?></pre>

##Controller
he<pre>public $helpers = array('Html', 'Form');</pre>
co<pre>public $components= array('Session');</pre>
admin
<pre>output default amin methods: admin_inde(), admin_edit() and admin_delete() </pre>

bf <pre> 
//beforeFilter
public function beforeFilter() {
    parent::beforeFilter();
    
}</pre>

bv
<pre>
	//Before Validate

	public function beforeValidate() {
	   
	    
	}
</pre>
