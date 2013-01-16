#FORM HELPER
fc ==> <?php echo $this->Form->create('Model', ); ?> <br />
fi ==> <?php echo $this->Form->input('fielName', array('label'=>'custom label'))); ?> <br />

#COMPONENT
he ==> public $helpers = array('Html', 'Form');
co ==> public $components= array('Session');