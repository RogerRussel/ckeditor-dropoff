# How change config.extraPlguins

This normally stay at config.js, but if it was not there you can just add into this folder.

An config.js file with this configuration should look like
<code>

CKEDITOR.editorConfig = function (config) {
  config.toolbarGroups = [
    {name: 'document', groups: ['mode', 'document', 'doctools']},
    {name: 'clipboard', groups: ['clipboard', 'undo']},
    {name: 'editing', groups: ['find', 'selection', 'spellchecker']},
    {name: 'forms'},
    {name: 'basicstyles', groups: ['basicstyles', 'cleanup']},
    {name: 'paragraph', groups: ['list', 'indent', 'blocks', 'bidi']},
    {name: 'align'},
    '/',
    {name: 'links'},
    {name: 'insert'},
    {name: 'styles'},
    {name: 'colors'},
    {name: 'tools'},
    {name: 'others'}
  ];

  config.removeButtons = 'Cut,Copy,Paste,Undo,Redo,Anchor,Underline,Subscript,Superscript';
  config.removeDialogTabs = 'link:advanced';
  config.extraPlugins = 'dropoff';
  config.disallowedContent = "img,script";
};

</code>
