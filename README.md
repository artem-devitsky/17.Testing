# 17.Testing

## HW06 tested by ansible-lint

```bash
ansible-lint -vv ./ansible_files/playbook.yaml 
DEBUG    Logging initialized to level 10
DEBUG    Options: Namespace(cache_dir='/home/user/.cache/ansible-lint/6d5eb3', colored=True, config_file=None, configured=True, cwd=PosixPath('/home/user/edu/devops_202205/17.Testing'), display_relative_path=True, enable_list=[], exclude_paths=['.cache', '.git', '.hg', '.svn', '.tox'], extra_vars=None, format='rich', kinds=[{'jinja2': '**/*.j2'}, {'jinja2': '**/*.j2.*'}, {'inventory': '**/inventory/**.yml'}, {'requirements': '**/meta/requirements.yml'}, {'galaxy': '**/galaxy.yml'}, {'reno': '**/releasenotes/*/*.{yaml,yml}'}, {'playbook': '**/playbooks/*.{yml,yaml}'}, {'playbook': '**/*playbook*.{yml,yaml}'}, {'role': '**/roles/*/'}, {'tasks': '**/tasks/**/*.{yaml,yml}'}, {'handlers': '**/handlers/*.{yaml,yml}'}, {'vars': '**/{host_vars,group_vars,vars,defaults}/**/*.{yaml,yml}'}, {'meta': '**/meta/main.{yaml,yml}'}, {'yaml': '.config/molecule/config.{yaml,yml}'}, {'requirements': '**/molecule/*/{collections,requirements}.{yaml,yml}'}, {'yaml': '**/molecule/*/{base,molecule}.{yaml,yml}'}, {'requirements': '**/requirements.yml'}, {'playbook': '**/molecule/*/*.{yaml,yml}'}, {'yaml': '**/{.ansible-lint,.yamllint}'}, {'yaml': '**/*.{yaml,yml}'}, {'yaml': '**/.*.{yaml,yml}'}], lintables=['./ansible_files/playbook.yaml'], listrules=False, listtags=False, loop_var_prefix=None, mock_modules=[], mock_roles=[], offline=None, parseable=False, parseable_severity=False, progressive=False, project_dir='.', quiet=0, rules={}, rulesdir=[], rulesdirs=['/usr/lib/python3.8/site-packages/ansiblelint/rules'], skip_action_validation=True, skip_list=[], tags=[], use_default_rules=False, var_naming_pattern=None, verbosity=2, version=False, warn_list=['experimental', 'role-name'])
DEBUG    /home/user/edu/devops_202205/17.Testing
DEBUG    Loading rules from /usr/lib/python3.8/site-packages/ansiblelint/rules
INFO     Executing syntax check on ansible_files/playbook.yaml (1.21s)
DEBUG    Examining ansible_files/playbook.yaml of type playbook

```
