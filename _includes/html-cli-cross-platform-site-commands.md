<table class="table table-striped cli cmd">
	<caption>{% include snippet-fun-consoleuser.md %}<kbd>azure site</kbd></caption>
	<tr>
		<th class="w20">command</th>
		<th class="w60">options</th>
		<th>description</th>
	</tr>
	<tr>
		<td>browse {% include command-argument-options.md %} {% include command-argument-name.md %}</td>
		<td>
			<dl class="dl-horizontal">
				{% include command-option-help.md %}
				{% include command-option-verbose.md %}
				{% include command-option-json.md %}
				{% include command-option-subscription.md %}
			</dl>
		</td>
		<td>launch the website [name] in the default browser</td>
	</tr>
	<tr>
		<td>create {% include command-argument-options.md %} {% include command-argument-name.md %}</td>
		<td>
			<dl class="dl-horizontal">
				{% include command-option-help.md %}
				{% include command-option-verbose.md %}
				{% include command-option-json.md %}
				{% include command-option-subscription.md %}
				{% include command-option-location.md %}
				{% include command-option-hostname.md %}
				{% include command-option-git.md %}
				{% include command-option-publishingusername.md %}			
				{% include command-option-github.md %}
				{% include command-option-githubusername.md %}
				{% include command-option-githubpassword.md %}
				{% include command-option-githubrepository.md %}
			</dl>
		</td>
		<td>create a new, or associate a local directory to an existing web site</td>
	</tr>
	<tr>
		<td>delete {% include command-argument-options.md %} {% include command-argument-name.md %}</td>
		<td>
			<dl class="dl-horizontal">
				{% include command-option-help.md %}
				{% include command-option-verbose.md %}
				{% include command-option-json.md %}
				{% include command-option-subscription.md %}
				{% include command-option-quiet.md %}
			</dl>
		</td>
		<td>delete the web site [name]</td>
	</tr>
	<tr>
		<td>set {% include command-argument-options.md %} {% include command-argument-name.md %}<p><span class="label label-warning">new</span></p></td>
		<td>
			<dl class="dl-horizontal">
				{% include command-option-help.md %}
				{% include command-option-verbose.md %}
				{% include command-option-json.md %}
				<dt>--net-version &lt;net-version&gt;</dt><dd>The .NET version. Valid options are v3.5 and v4.5</dd>
				<dt>--php-version &lt;php-version&gt;</dt><dd>The PHP version. Valid options are off, v5.3 and v5.4</dd>
				{% include command-option-subscription.md %}
			</dl>
		</td>
		<td>Sets configuration options for your web site [name]</td>
	</tr>
	<tr>
		<td>show {% include command-argument-options.md %} {% include command-argument-name.md %}</td>
		<td>
			<dl class="dl-horizontal">
				{% include command-option-help.md %}
				{% include command-option-verbose.md %}
				{% include command-option-json.md %}
				{% include command-option-subscription.md %}
			</dl>
		</td>
		<td>Show details for a web site</td>
	</tr>
	<tr>
		<td>start {% include command-argument-options.md %} {% include command-argument-name.md %}</td>
		<td>
			<dl class="dl-horizontal">
				{% include command-option-help.md %}
				{% include command-option-subscription.md %}
				{% include command-option-verbose.md %}
				{% include command-option-json.md %}
			</dl>
		</td>
		<td>start the Internet Information Services (IIS) site</td>
	</tr>
	<tr>
		<td>stop {% include command-argument-options.md %} {% include command-argument-name.md %}</td>
		<td>
			<dl class="dl-horizontal">
				{% include command-option-help.md %}
				{% include command-option-subscription.md %}
				{% include command-option-verbose.md %}
				{% include command-option-json.md %}
			</dl>
		</td>
		<td>stop the Internet Information Services (IIS) site</td>
	</tr>
	<tr>
		<td>restart {% include command-argument-options.md %} {% include command-argument-name.md %}</td>
		<td>
			<dl class="dl-horizontal">
				{% include command-option-help.md %}
				{% include command-option-subscription.md %}
				{% include command-option-verbose.md %}
				{% include command-option-json.md %}
			</dl>
		</td>
		<td>stop, then start the Internet Information Services (IIS) site</td>
	</tr>
</table>