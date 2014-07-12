guard 'shell' do
  # builds latex file to pdf and hides output
  watch(/(.*).tex/) do |m|
    system 'make 2>&1'
    puts "built #{m[1]}.pdf Errores: #{err}"
  end
end
