# Notes/Summary

- Arguments create new local variables that can be used within the method.
- Once you define arguments for a method, they become required when you invoke or call the method.

omitting the parentheses helps to clear things up. You might also see some Domain Specific Languages (DSLs) that prefer to omit parentheses. You've probably already seen a little bit of RSpec's DSL, for example:

```ruby
describe "MyRubyThing" do
  it "runs" do
    # test here
  end
end
```

`describe` and `it` are just methods — the above could have been written

```ruby
describe("MyRubyThing") do
  it("runs") do
    # test here
  end
end
```

but I think you'll agree that it looks nicer (and is easier to read) without the parentheses.