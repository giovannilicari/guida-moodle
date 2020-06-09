# modifica file /course/classes/output/activity_navigation.php

nel seguente file

../course/classes/output/activity_navigation.php

aggiungere

 'style' => 'white-space:pre-wrap',
 
in corrispondenza prevlink e nextlink 
 
'class' => 'btn btn-link',
                'id' => 'prev-activity-link',
                'title' => $linkname,
                'style' => 'white-space:pre-wrap',
            ];
            $this->prevlink = new \action_link($linkurl, $OUTPUT->larrow() . ' ' . $linkname, null, $attributes);
