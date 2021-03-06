# Puppeteer Snippets Extension 

ghoul007-puppeteer-snippet provides basic snippet support for Puppeteer for vscode.
[see more](https://marketplace.visualstudio.com/items?itemName=ghoul007.ghoul007-puppeteer-snippet&ssr=false#overview)


## Snippets List

| Snippet            | Content                                |
| ------------------ | -------------------------------------- |
|  `g-import-puppeteer→`  |    require('puppeteer');
|  `g-import-module→`   |    require('...')                   
|  `g-import-firefox→`   |   require('puppeteer-firefox');                  
|  `g-launch→`   |   await puppeteer.launch();                   
|  `g-launch-headless→` | await puppeteer.launch({headless:false});                   
|  `g-browser-close→`   |    await browser.close();                    
|  `g-iife→`   |                (async()=>{ ... })()     
|  `g-browser-Incognit→`   |  await browser.createIncognitoBrowserContext();                  
|  `g-newPage→`   |           await browser.newPage();         
|  `g-waitForTarget→`   |     await browser.waitForTarget(...);                
|  `g-page$→`   |             await page.$('...');        
|  `g-page$$→`   |             await page.$$('...');        
|  `g-page-$eval→`   |          await page.$eval('...', ele => {,	...,});           
|  `g-page-$$eval→`   |        await page.$$eval('...', eles => {,	...,});             
|  `g-page-click→`   |          await page.click('...');           
|  `g-page-close→`   |          await page.close();           
|  `g-page-emulate→`   |        await page.emulate(...);            
|  `g-page-focus→`   |           await page.focus('...');          
|  `g-page-goBack→`   |           await page.goBack();          
|  `g-page-goForward→`   |        await page.goForward();             
|  `g-page-goto→`   |               await page.goto('...');      
|  `g-page-hover→`   |              await page.hover('...');       
|  `g-page-keyboard-down→`   |        await page.keyboard.down('...');             
|  `g-page-keyboard-up→`   |          await page.keyboard.up('...');           
|  `g-page-keyboard-press→`   |       await page.keyboard.press('...');              
|  `g-page-keyboard-sendCharacter→`   |    await page.keyboard.sendCharacter('...');                 
|  `g-page-keyboard-type→`   |              await page.keyboard.type('...');       
|  `g-pdf→`   |                     await page.pdf({ path: 'test.pdf', format: '... });
|  `g-screenshot→`   |              await page.screenshot({ path: 'test.png'});       
|  `g-waitFor→`   |                 await page.waitFor(...);   
|  `g-waitForFunction→`   |          await page.waitForFunction(...);           
|  `g-waitForNavigation→`   |         await page.waitForNavigation();            
|  `g-waitForRequest→`   |            await page.waitForRequest(...);         
|  `g-waitForResponse→`   |           await page.waitForResponse(...);          
|  `g-waitForSelector→`   |           await page.waitForSelector('...');          
|  `g-waitForXPath→`   |  await page.waitForXPath('...');
|  `g-event-document-loaded→`   |  page.once('domcontentloaded'...);
|  `g-event-load→`   |  page.once('load'...);
|  `g-event-console→`   |  page.on('console'...);
|  `g-event-metrics→`   |  page.on('metrics'...);
|  `g-event-error→`   |  page.on('error'...);
|  `g-fonction-sleep→`   |  const sleep = duration =>...;
|  `g-examples-basic→`   |  basic example...
|  `g-examples-pdf→`   |  example with PDF...
|  `g-examples-screenshot→`   |  example with screenshot...
|  `g-examples-basic-firefox→`   | example with firefox...
|  `g-examples-mobile-emulate→`   | example with mobile emulate...
