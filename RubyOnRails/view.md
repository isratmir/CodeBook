#View

###Form

#####Adding class to form and to elements

```ruby
<%= form_for @article, html: {class: "form"} do |f| %>
	<div class="form-group">
      <%= f.label :title %><br>
      <%= f.text_field( :text, {:class => "form-control"}) %>
    </div>
    <%= f.submit({:class => "btn"}) %>
<% end %>
```

###Links

#####Adding class to links

```ruby
	<%= link_to 'Show', article_path(article), class: "btn btn-default"  %>
```