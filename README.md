# CSerializeBehavior

@author Kenrick Buchanan <nsbucky@gmail.com>

@license http://www.yiiframework.com/license/

CSerializeBehavior allows a model to specify some attributes to be arrays and serialized upon save and unserialized after a Find() function is called on the model.

<pre>
public function behaviors()
{
    return array(
        'CSerializeBehavior' => array(
            'class' => 'application.behaviors.CSerializeBehavior',
            'serialAttributes' => array('validator_options'),
        )
    );
}
</pre>