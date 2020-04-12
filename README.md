# Puppeteer Snippets

ghoul007-puppeteer-snippet provides basic snippet support for Puppeteer for vscode.


## Snippets List

| Snippet            | Content                                |
| ------------------ | -------------------------------------- |
|   `g-ip→`  |    require('puppeteer');
|  `g-im→`   |    require('...')                   
|  `g-ipf→`   |   require('puppeteer-firefox');                  
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