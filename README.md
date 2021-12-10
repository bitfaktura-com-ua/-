## BitFaktura.com.ua - рахунки-фактури в Інтернеті
### Шаблони рахунків-фактур

Виставляючи рахунки-фактури в нашій програмі, ви маєте доступ до кількох шаблонів цього документу. Якщо якийсь із них не відповідає вашим очікуванням, ви можете підготувати власний шаблон. Просто увійдіть у свій обліковий запис (якщо у вас його ще немає, [ви можете створити безкоштовний обліковий запис тут](https://app.bitfaktura.com.ua/signup)) і перейдіть до **Налаштування> Налаштування акаунта> Шаблони**. Потім натисніть «Додати новий шаблон» – відкриється вікно редагування коду, завдяки якому ви зможете підготувати індивідуальний шаблон.

Шаблони створюються за допомогою тегів [Handlebars](http://handlebarsjs.com/)
Змінні, які можна використовувати в шаблонах:

``` 
{{absolute_outstanding}}
{{absolute_outstanding_in_exchange_currency}}
{{absolute_outstanding_in_words}}
{{absolute_outstanding_in_words_in_exchange_currency}}
{{accounting_doc}}
{{accounting_note_kind}} - підтип
{{additional_address_seller_name}} - додаткова адреса постачальника
{{additional_field_name}} – назва додаткового поля
{{additional_field_value}} - вартість додаткового поля
{{additional_info}} – додаткова інформація
{{additional_info_desc}} - додаткове поле для позицій в рахунках-фактурах
{{address}} - адреса
{{advanced}} - 
{{advanced_num}}
{{advanced_total_price_gross}}
{{all_in_words}} - словами
{{all_in_words_in_exchange_currency}} - словами в конвертованій валюті
{{bank}} - банк
{{bank_account}} - банківський номер
{{bilangual}} - двомовний
{{buyer}} - платник
{{buyer_address}} - адреса замовника
{{buyer_bank_account}} - обліковий запис платника
{{buyer_company}} - компанія платника
{{buyer_country}} - країна платника
{{buyer_country_code}} - код країни платника
{{buyer_email}} - e-mail платника
{{buyer_first_name}} - Ім’я
{{buyer_last_name}} - Прізвище
{{buyer_mobile_phone}} - номер телефону
{{buyer_note}} - додатковий опис
{{buyer_person}} - ім’я та прізвище платника
{{buyer_phone}} - телефон клієнта
{{buyer_place}}
{{buyer_post_code}} - поштовий код
{{buyer_register_number}} - ЄДРПОУ
{{buyer_street}} - вулиця і номер
{{buyer_tax_no}} - ІПН
{{buyer_tax_no_kind}} - тип ідентифікаційного номера платника
{{cancel_reason}} - причина анулювання рахунку-фактури
{{canceled}} - скасовано
{{client_external_id}} - ID клієнта (зовнішнє)
{{{client_panel_view_link}}} - посилання на панель клієнта
{{{client_panel_view_link_unpaid}}} - посилання на панель клієнта (неоплачені)
{{client_panel_view_url}} - посилання на панель клієнта url
{{client_url}} - url клієнта

{{company}} - компанія
{{corrected_content_after}} - правильний вміст
{{corrected_content_before}} - скоригований вміст
{{corrected_issue_date}} - поправлена дата випуску
{{corrected_kind}} - скоригований тип
{{corrected_number}} - скоригований номкр
{{correction}} - виправлений документ
{{correction_reason}} - причина виправлення
{{country}} - країна
{{created_at}} - створення
{{currency}} - валюта
{{currency_short}} - валюта (коротка)
{{currency_symbol}} - валюта (символ)
{{delivery_address}} - адресат
{{delivery_address_name}} - адреса доставки
{{description_footer}} - додаткові нотатки (друковані внизу сторінки)
{{description_long}} - додаткові нотатки (друковані на другій сторінці)
{{discount}} - знижка
{{discount_kind}} - тип знижки
{{document_type}} - тип документа
{{email}} - адрес електронної почти
{{exchange_currency}} - конвертація валюти
{{exchange_currency_rate}} - курс
{{exchange_date}} - дата обміну валюти
{{exchange_note}} - нотатка для курсу
{{exchange_tax}} - податок з конвертації
{{exempt_tax_kind}}
{{fax}}
{{final}}
{{footer}} - {:generated_in=>"створено в %{domain}", :page=>"сторінка", :page_of=>" з "}
{{forced_payment_to}}
{{from_recurring_payment}}
{{global_discount_gross}}
{{global_discount_gross_with_currency}}
{{global_discount_net}}
{{global_discount_net_with_currency}}
{{has_corrected_content}}
{{hide_tax}} - приховати податок і ціну без ПДВ
{{id}}
{{income}} - доходи
{{internal_note}} - приватна нотатка (не видно на роздруківці)
{{invoice_category}} - категорія рахунка-фактури
{{issue_date}} - дата випуску
{{issue_place}} - місце виставлення
{{issuer}} - особа, яка виставила
{{kind}} - тип
{{lang}} - мова
{{legal_cost_compensation}}
{{locale}} - регіон
{{logo_url}}
{{long_exchange_note}}
{{long_exchange_note_for_tax}}
{{negative_outstanding}}
{{notes}} - нотатки
{{number}} - номер
{{oid}} - номер замовлення
{{outstanding}}
{{outstanding_in_exchange_currency}}
{{outstanding_in_words}}
{{outstanding_in_words_in_exchange_currency}}
{{overdue}} - прострочений
{{paid}} - оплачено
{{paid_date}} - дата оплати
{{paid_mark_url}}
{{payment_button_url}} - посилання кнопки оплати
{{{payment_link}}} - посилання на оплату
{{payment_reference_number}} - номер платежу
{{payment_to}} - дата оплати
{{payment_url}} - посилання оплати
{{payments}} - {:header=>"płatności", :by=>"przez"}
{{person}}
{{phone}} номер телефону
{{place}} - місце випуску
{{positions_total_price_gross}}
{{positions_total_price_net}}
{{positions_total_quantity}}
{{positions_total_quantity_separated}}
{{positions_total_tax}}
{{positions_total_weight}}
{{positons_total_tax}}
{{post_code}} - поштовий код
{{prepayment_required}} - вимагана передоплата (%)
{{prepayment_required_exact_amount}} - точне значення
{{print_option}}
{{procedure_designations_list}}
{{procedure_designations_note}}
{{product_cache}}
{{proforma}} - рахунок-проформа
{{qrcode_img}}
{{receipt}}
{{recipient_address}} - адреса отримувача
{{recipient_city}} - місто
{{recipient_country}} - країна
{{recipient_name}} - одержувач
{{recipient_note}} - додатковий опис
{{recipient_phone}} - номер телефону
{{recipient_post_code}} - поштовий код
{{recipient_present}}
{{recipient_street}} - вулиця і номкр
{{recipient_url}}
{{reminder_no}} - кількість надісланих неоплачених нагадувань до рахунків-фактур
{{reminder_number}} - номер нагадування
{{reverse_charge_code}} - код транзакції
{{sales_code}}
{{sec_stamp_url}}
{{sell_date}} - дата продажу
{{sell_date_MY}}
{{sell_date_kind}}
{{seller_register_number}} - ЄДРПОУ
{{seller_tax_no_kind}}
{{should_print_procedure_designations}}
{{show_buyer_note}}
{{show_date_and_sign}}
{{show_discount}}
{{show_empty_buyer_person}}
{{show_empty_seller_person}}
{{show_links}}
{{show_paid_date}}
{{show_paid_logo}}
{{show_paid_when_zero}}
{{show_payments_on_invoice}}
{{show_product_description}}
{{show_sell_date}}
{{show_tax_split}}
{{show_totals}}
{{show_unit_price_gross}}
{{sign_document_url}}
{{signature_date}}
{{signature_url}}
{{split_payment}} - механізм роздільного платежу
{{split_payment_note}}
{{stamp_below_sign_url}}
{{stamp_url}}
{{status_paid}}
{{street}}
{{subscription_count}}
{{subscription_day_of_month}}
{{subscription_month}}
{{swift}}
{{tax2_details}}
{{tax2_name}}
{{tax2_visible}}
{{tax_in_exchange_currency}}
{{tax_name}}
{{tax_no}} - nip
{{tax_value}}
{{tax_value_in_exchange_currency}}
{{tax_value_in_exchange_currency_with_currency}}
{{tax_value_name}}
{{tax_value_with_currency}}
{{tax_visible}}
{{title}} - заголовок
{{today_date}}
{{token}}
{{total_discount}}
{{total_discount_in_exchange_currency}}
{{total_discount_in_exchange_currency_with_currency}}
{{total_discount_with_currency}}
{{total_price_gross}} - wartość brutto
{{total_price_gross_in_exchange_currency}}
{{total_price_gross_in_exchange_currency_with_currency}}
{{total_price_gross_in_main_currency}}
{{total_price_gross_with_currency}}
{{total_price_gross_without_discount}}
{{total_price_gross_without_discount_with_currency}}
{{total_price_net}} - wartość netto
{{total_price_net_in_exchange_currency}}
{{total_price_net_in_exchange_currency_with_currency}}
{{total_price_net_in_main_currency}}
{{total_price_net_with_currency}}
{{total_price_net_without_discount}}
{{total_price_net_without_discount_with_currency}}
{{total_tax_inscription}}
{{transaction_id}}
{{type_of_payment}}
{{use_barcodes}}
{{use_delivery_address}} - інша поштова адресуа
{{use_paid_dates}}
{{use_product_code}}
{{{view_link}}}
{{view_url}}
{{www}}
{{zero_with_currency}}
{{zero_with_currency_in_exchange_currency}}

{{#each final_summary}} :
{{tax}}
{{tax_value}}
{{tax_value_with_currency}}
{{total_price_gross}}
{{total_price_gross_with_currency}}
{{total_price_net}}
{{total_price_net_with_currency}}
{{/each}}

{{#each positions}} :
{{accounting_activity_code}}
{{accounting_code_expenses}}
{{accounting_code_income}}
{{accounting_code_sales}}
{{accounting_code_tax_purchase}}
{{accounting_code_tax_sale}}
{{additional_info}} - значення додаткового поля на позиціях рахунків-фактур
{{additional_info_desc}}
{{barcode}}
{{code}} - код продукту
{{description}} - опис
{{discount}} - сума знижки
{{discount_amount_gross}}
{{discount_amount_net}}
{{ean_code}}
{{has_discount}}
{{image_url}}
{{item}} - назва продукту/послуги
{{item_url}}
{{kind}} - тип позиції
{{no}}
{{quantity}} - кількість
{{quantity_number}}
{{quantity_unit}} - одиниця
{{supplier_code}}
{{tax}} - ставка ПДВ
{{tax1_value_name}}
{{tax2}} - stawka vat
{{tax2_name}}
{{tax2_value_name}}
{{tax_name}}
{{tax_value}} - сума ПДВ
{{tax_value_name}}
{{total_price_gross}} - сума з ПДВ
{{total_price_gross_without_discount}}
{{total_price_net}} - сума без ПДВ
{{total_price_net_without_discount}}
{{unit_price_gross}}
{{unit_price_gross_with_discount}}
{{unit_price_net}}
{{unit_price_net_with_discount}}
{{/each}}

{{#each summary}} :
{{tax}}
{{tax_value}}
{{tax_value_with_currency}}
{{total_price_gross}}
{{total_price_gross_with_currency}}
{{total_price_net}}
{{total_price_net_with_currency}}
{{/each}}

{{additional_fields}} :
{{additional_fields.seller_bank_swift}}
{{additional_fields.tax_name}}
{{additional_fields.tax_name_type}}

{{client}} :
{{client.accounting_id}} - ID в бухгалтерській програмі
{{client.additional_accounting_id}}
{{client.discount}} - знижка за замовчуванням %
{{client.email}} - e-mail
{{client.first_name}} - ім’я
{{client.last_name}} - прізвище
{{client.name}} - назва підприємства
{{client.panel_link}}
{{client.panel_link_unpaid}}
{{client.panel_url}} - посилання на панель клієнта

{{department}} :
{{department.bank_account}} - банківський рахунок
{{department.bank_iban}} - iban
{{department.bank_name}}
{{department.bank_swift}} - swift
{{department.capital}}
{{department.capital_currency}}
{{department.capital_kind}} - Акціонерний капітал
{{department.footer_content}} - вміст нижнього колонтитула
{{department.footer_kind}}
{{department.id}}
{{department.kind}} - юридична форма
{{department.name}} - назва компанії або відділу
{{department.own_footer}} - власний вміст нижнього колонтитула
{{department.tax_kind}} - тип податкового номера відділу
{{department.tax_no}} - номер ІПН

{{subscription_interval_unit}} :
{{subscription_interval_unit.monthly}} - щомісяця
{{subscription_interval_unit.weekly}} - кожного тиж
{{subscription_interval_unit.yearly}} - щороку

{{footer}}
```

## Шаблони повідомлень email
Ви можете створити шаблони електронної пошти, які надсилатимуться клієнтам. Є два шаблони для стандартної відправки рахунків-фактур і для надсилання нагадувань про неоплачені рахунки. Під час створення шаблонів ви використовуєте ті самі змінні, що й для шаблонів рахунків-фактур, а також використовуєте Handlebars.
Шаблон за замовчуванням для надсилання рахунків-фактур:

``` 
Добрий дня,

дякуємо за користування нашими послугами.
Додаю документ
{{document_type}} {{number}} в вартості {{total_price_gross}} з ПДВ.

Посилання для перегляду: {{view_url}}


{{footer}}
``` 

Шаблон нагадування про неоплачений рахунок-фактуру за умовчанням:
``` 
Добрий дня,

нагадуємо про прострочення платежу
{{document_type}} {{number}} в сумі {{total_price_gross}} з ПДВ.

Посилання для перегляду: {{view_url}}

{{footer}}
``` 

## Функції доступні в шаблонах рахунків-фактур та електронних листів
У шаблонах доступні такі функції: 
 if
  for
  eq
  not_eq
  lt
  gt
  or
  and
  tt
  include
  include_in_col
  in
  not_in
  to_uppercase
  replace
  inc
  dec
  abs
  if_created_after_date
  inline_partial

Приклад виклику функції:
``` 
{{#if val1 }}
  ok
{{else}}
  not ok
}}

{{#lt val1 17 }}
  <17
}}

{{#gt val1 17 }}
  >17
{{else}}
 <17
}}

{{#eq department_id "123"}}
  інформація для відділу
{{else}}
 інформація для інших відділів
{{/eq}}

{{#for size_from size_to}}
    no: {{no}}
{{/for}}

{{inline_partial "partial1" "{{document_type}} {{number}}: {{total_price_gross_with_currency}} {{tt 'invoice.gross'}}<br>"}}
{{>partial1}}

{{#inline_partial "partial2"}}
  {{#eq lang "pl"}}
  Добрий дня,
  {{else}}
    Hello,
  {{/eq}}
  {{>partial1}}
{{/inline_partial}}
{{>partial2}}
``` 
## Імпорт даних

Можна імпортувати дані з будь-яких програм, які зберігатимуть дані у файли .TXT, .CSV, .XLS, .ODS, .XLSX, .TSV, .XML. Під час імпорту ви можете вказати, які стовпці та рядки імпортувати.

Ви можете імпортувати рахунки-фактури, клієнтів, продукти

## API
Опис API можна знайти тут: [BitFaktura API](https://github.com/bitfaktura-com-ua/API)


